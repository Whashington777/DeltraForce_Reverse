# Исследование сборки Delta Force

Пакет `com.proxima.dfm`, версия `1.202.37117.5601` (2217), ARM64.
Build ID: `0165b78b19f52f4ee20357ff54eb93da19b44407`.
Все адреса ниже — смещения относительно начального отображения libUE4.so этой сборки.

## Подтверждено в текущем процессе

- `0x2076B918`: глобальный слот указателя на таблицу блоков объектов.
- `0x2076B90C`: число элементов, при проверке 219733.
- Размер записи объекта: `0x18`; блок содержит 65536 записей.
- В объекте поле индекса находится по `+0x24`.
- Для первых восьми объектов индекс совпал с номером записи.
- Маркер движка в памяти: `++UE4+Release-4.24`.

Это не определяет начало полной структуры GUObjectArray: найденные адреса относятся к её полям.

## Кандидат

`0x20AA87A0`: слот указателя, используемый в функции с диагностикой GWorld-is-null. Указатель ненулевой, объект имеет индекс 116020 и совпадает с соответствующей записью таблицы объектов. Тип World ещё не подтверждён, поэтому адрес нельзя считать готовым проверенным GWorld.

## Метод и ограничения

Исследование только чтением: ELF из установленного APK, карта памяти, участки кода и констант загруженной библиотеки, точечные чтения объектов. Содержимое загруженных участков отличается от файла APK. Найдены ссылки ADRP/ADD на диагностические строки; дизассемблирование сохранено в string-references.json. Записей в память процесса не было.

Адрес начала отображения при исследовании: `0x78D4626000`, PID 18233. Это временные значения. Повторная проверка после перезапуска и поиск таблицы имён ещё не выполнены. Скрипты inspect_candidates.py и find_string_refs.py являются исследовательскими и привязаны к сохранённому снимку, не готовы для лоадера.

## Проверка после перезапуска

Новый PID: 22846, начальное отображение `libUE4.so`: `0x78D6C43000`.
Те же смещения таблицы работают: 180176 объектов, 3 блока. Проверены 11 записей, включая начала второго и третьего блоков и последнюю запись: все индексы совпали.
Кандидат `0x20AA87A0` теперь содержит `0x7866841BE0`, индекс 113081; запись таблицы совпадает. Это подтверждает повторяемость слота после одного перезапуска, но не подтверждает тип World.
Полные данные: `restart-verification.json`. Предыдущие исследовательские скрипты с фиксированным PID не следует запускать как актуальные проверки.

## Подтверждение World и массива PlayerState в матче

В PID 22846 кандидат `base + 0x20AA87A0` подтверждён как объект класса `World`, имя `Cracked_Breakthrough`. Это уточняет прежний статус кандидата выше.

Цепочка чтения:

1. `world = *(base + 0x20AA87A0)`.
2. `game_state = *(world + 0x140)`, класс `BP_GameState_Breakthrough_C`.
3. `player_states = *(game_state + 0x388)`.
4. `count = int32(game_state + 0x390)`.
5. Каждый элемент — 8-байтный указатель, `player_states[i]`.

При повторном чтении проверены все 48 элементов: все есть в таблице объектов и имеют класс `BP_BattleFieldPlayerState_C`. Адреса заголовков и счётчик оставались стабильны в пределах проверки. Это массив состояний участников, не подтверждение живых персонажей/Pawn.

Также подтверждены `world + 0xF8` как Level с именем PersistentLevel и `world + 0x190` как BP_DFMGameInstance_C. Наблюдаемый пул имён расположен по `base + 0x20744AC0`, таблица блоков `+0x38`. Поля UObject: указатель класса `+0x8`, FName `+0x1C`, индекс объекта `+0x24`. Исследовательский декодер имён выбирал читаемый ASCII из наблюдаемых вариантов; универсальным декодером его считать нельзя.

Полная повторная проверка: `player-roster-verification.json`. Цепочка GameState/PlayerState проверена только в текущем матче Breakthrough; повторный запуск и другие режимы для неё ещё не проверены.

## Команды и локальный игрок в Breakthrough

Поля получены из отражённых свойств классов, смещение Offset_Internal `FProperty + 0x4C`:

- `GPPlayerState.TeamID`: `PlayerState + 0x658`, int32, в этом матче 12 групп по 4.
- `GPPlayerState.Camp`: `PlayerState + 0x65C`, int32, в этом матче стороны 0 и 1, по 24 участника.
- `PlayerState.PawnPrivate`: `PlayerState + 0x3F8`, указатель (связь с персонажами ещё отдельно не проверялась).
- `Controller.PlayerState`: `Controller + 0x378`, указатель.

Локальная цепочка: `world -> +0x190 GameInstance -> +0x38 LocalPlayers.data -> первый элемент LocalPlayer -> +0x30 PlayerController -> +0x378 PlayerState`.
Локальный PlayerState совпал с записью массива, его Camp=0, TeamID=0. По сравнению Camp получено: 1 свой объект, 23 союзника, 24 противника. По сравнению Camp и TeamID вместе — отряд из 4, включая себя.

В этом режиме различие TeamID само по себе не означает противника: союзники находятся в разных отрядах. Неизвестные Camp нужно оставлять неклассифицированными. Семантика стороны подтверждается именем свойства и распределением 24/24; независимое сравнение с экранными метками не выполнено. Другие режимы и перезапуск для всей локальной цепочки не проверены.

Доказательства и все 48 записей без пользовательских имён: `team-partition-verification.json`. Исследовательские скрипты пока не являются стабильным runtime-компонентом для GUI.

## Эвакуация / PVPVE — отдельная проверка

Карта World `Iris_Entry`, класс GameState `BP_GameState_PVPVE_C`, класс участников `BP_SOLPlayerState_C`. Поле PlayerArray найдено по метаданным `GameStateBase.PlayerArray`, смещение `+0x388`: совпало с прежним режимом. Общие смещения World/GameInstance/LocalPlayer/Controller/PlayerState также прочитались корректно.

**Правило Camp из Breakthrough не применимо:** обнаружен BP_SOLPlayerState_C с Camp=0, но TeamID=2, при локальных Camp=0 и TeamID=1. Для эвакуации отношения определяются сравнением TeamID, с проверкой класса и валидности объекта. Это вывод из метаданных и группировки отрядов; независимая сверка с экранными метками не выполнена.

В повторном снимке 14 записей: 1 локальный PlayerState, 2 с тем же TeamID=1, 10 BP_SOLPlayerState_C из других команд, 1 GPPlayerState с Camp=-1 оставлен неизвестным. World, GameState и заголовок PlayerArray стабильны в течение чтения. Значения Camp 106 не интерпретируются как AI: соответствующий признак не подтверждён.

Список PlayerState не равнозначен списку активных живых персонажей. Связь PawnPrivate, жизнеспособность и повторная проверка других матчей остаются отдельными задачами. Полные результаты: `evacuation-team-verification.json`; отдельный набор смещений и ограничений: `evacuation-offsets.json`.

## Связь участников с персонажами и NPC

Подтверждены по метаданным Pawn: `PlayerState +0x390`, `Controller +0x3A8`; по PlayerState: `PawnPrivate +0x3F8`. Ссылки проверены в обе стороны у доступных персонажей.

Для персонажей участников цепочка класса содержит `DFMPlayerCharacter`. Для NPC — `DFMAICharacter`; животные проходят через `DFMAIAnimalCharacter -> DFMAICharacter`. Это проверка цепочки наследования, а не только слова AI в имени класса.

Сканирование PersistentLevel: `world +0xF8 -> level`, `level +0x98 -> actors.data`, `level +0xA0 -> count`, шаг 8 байт. Обнаружены классы обычных AI-бойцов, огнемётчиков, щитоносцев, RPG и крокодилов. Показатели меняются во время матча.

Последний полный снимок текущего PersistentLevel: PlayerState содержит себя, 2 союзников и 10 участников других команд; доступны Pawn себя и 3 участников других команд; найдены 9 NPC (7 DT, 1 Firebat, 1 Crocodile). Все доступные Pawn вернулись на соответствующий PlayerState, а PlayerState.PawnPrivate вернулся на тот же Pawn. Заголовки World/GameState/PlayerArray/Actors стабильны в пределах чтения.

Не все записи PlayerState имеют доступный Pawn. Это не доказывает смерть, отсутствие игрока или его видимость. Сканирование не охватывает все streamed levels. NPC-класс сам по себе не определяет враждебность NPC. Исследовательский снимок и скрипты пока не являются готовым модулем GUI.

Основные доказательства: `actor-type-metadata.json`, `evacuation-entity-snapshot.json`; повторяемый исследовательский сбор: `capture_entity_snapshot.py`.

## Позиция, камера и геометрия капсулы

Поля найдены по метаданным. `PlayerController.PlayerCameraManager +0x408` ведёт к BP_TestPlayerCameraManager_C. `CameraCachePrivate +0x2D60` — CameraCacheEntry; `POV +0x10` — MinimalViewInfo. Итоговые поля относительно CameraManager: Location `+0x2D70`, Rotation `+0x2D80`, FOV `+0x2D8C`, AspectRatio `+0x2DA0`.

Позиция RootComponent: RelativeLocation `+0x168`, **EncVector размером 16 байт**, не обычный FVector из 12 байт. Поля-кандидаты XYZ по 0/4/8, EncHandler uint32 по +0xC. AttachParent `+0x108`. Для CapsuleComponent: CapsuleHalfHeight `+0x5C0`, CapsuleRadius `+0x5C4`.

10 независимых чтений во время движения подтвердили изменение позиции и камеры; локальные EncHandler были 0xFFFF. Камера находится рядом с персонажем, высота капсулы менялась между 86 и 60, FOV между 90 и ~17.49. Это подтверждает локальный случай, а не универсальный декодер EncVector.

Другие участники имели EncHandler вида 0x0300FFxx: raw XYZ конечны и похожи на координаты, но их интерпретация пока не подтверждена независимой проверкой. У проверенных RootComponent AttachParent=0. У NPC-крокодила наблюдался EncHandler=0xFFFF, HalfHeight=Radius=40.

WorldToScreen/ориентация осей/соответствие пикселям пока не проверены. Файлы: `geometry-offsets.json`, `motion-samples.json`, `position-struct-layouts.json`, `position-target-verification.json`.

## New evacuation match coordinate comparison
Four captures: stable World 0x78b48c7720, local TeamID 1, 16 roster entries and 9 active player Pawns (self, two allies, six other-team players). Reflection confirms Actor.ReplicatedMovement+0x9C / RepMovement.Location+0x18 = Actor+0xB4. Remote candidates have handler 0xFFFF and several change across captures. This alone does not validate world coordinates: remote heights differ substantially from the local camera and some locations remain stale. Root relative coordinates retain encoded handlers 0x030100xx. Screen candidates are diagnostic calculations, not validated boxes. Evidence: new-match-position-comparison.json and replicated-position-new-match.json.

## Teammate visible capture
Saved teammate-held.png and teammate-held-paired.png with accompanying memory JSON. Visible nearby teammate does not agree with projected ReplicatedMovement.Location. The second capture gives ally candidates behind the sampled camera, despite a visible nearby ally. Camera yaw also differs from screenshot compass; sequential ADB acquisition is not frame synchronized. Neither remote positions nor camera interpretation are pixel-validated. Do not infer a fixed Z correction from these captures.

## Camera source and rotation audit
Live reflected Rotator confirms pitch+0, Yaw+4, Roll+8. CameraCache and LastFrameCameraCache are zero/unpopulated in the current World; private caches hold populated POV and timestamps 91.139114 / 91.105774. Two 20KiB contiguous reads took approximately 84ms and 79ms. Private cache timestamp did not advance between these reads, so this observation does not prove an actively updating scene. This excludes a rotation-field ordering error and avoids selecting empty public caches; it does not validate remote XYZ or screen alignment.

## Movement component alternatives
Reflected SOLPlayerMovementComponent fields: LastUpdateLocation+0x2A0 (16 bytes), LastClientAckedLocation+0x10F8, TargetClientAckedLocation+0x1104, CurClientLocation+0x1110 (12 bytes each). LastFrameWorldPosition at Pawn+0x1D10 is also 16 bytes. Movement pointers Pawn+0x3D8 / +0x1B38 / +0x2680 agreed in a subsequent capture. Three captures show acked locations unchanged, including the moving local Pawn; one remote acked field remains all zero. They are not established current positions. An approximate 180m distance agreement in one frame is insufficient. Screenshot collection took approximately four seconds and camera yaw changed about 162 degrees between bracketing reads, invalidating that frame pairing. Evidence: movement-position-metadata.json, movement-component-fields.json, movement-bracket.json, acked-location-motion.json.

## Dynamic dependence and mesh bounds checks
12 fresh samples recorded per-read acquisition times for ReplicatedMovement.Location, Root.RelativeLocation, LastFrameWorldPosition and movement LastUpdateLocation. Several remote fields track local motion with small relative variation and large persistent Z displacement; this is evidence against treating handler-FFFF candidates as established independent world positions, not proof of a particular protection mechanism. Per-field mean/std summaries are in position-dependence-statistics.json. Reflected SkinnedMeshComponent.CachedWorldSpaceBounds+0x8E8 is 28 bytes; it was zero for all 11 freshly discovered player meshes, so it is unusable in these captures. The original mesh targets changed validity during inspection; fresh roster acquisition was required. Evidence: position-dependence-samples.json, mesh-position-metadata.json, fresh-roster-mesh-bounds.json.

## Reader validation correction
Important measurement bug: earlier end-of-sample q()/i() checks reused cached pages, so stable_world/stable_roster were cached equality checks rather than fresh validation. Old coordinate snapshots now explicitly say epoch_stability_verified=false. compare_match_positions.py clears cache before end checks; fresh-epoch-validation.json passed freshly read World and roster-header equality with local TeamID 2 and 5 active Pawns. Header equality still does not make page reads atomic or ensure every roster element remained unchanged. Cached bone/component-space arrays at mesh+0xA08/+0xA18 were empty in five inspected meshes. No world-position source has been pixel-validated.

## Own scoped reflection dumper
Created dump_reflected_geometry.py and refinement/export steps. Own export contains 555 types: 44 classes and 511 structs, 5702 reflected properties, 1586 functions. Three reused non-UStruct addresses were removed and 58 ambiguous short field names resolved. Fourteen geometry-layout checks against earlier captured metadata pass. This is a scoped export, not a full generated SDK.
Native exec functions: Actor.K2_GetActorLocation RVA 0x115A16DC, SceneComponent.K2_GetComponentLocation RVA 0x11CF37D8, SceneComponent.K2_GetComponentToWorld RVA 0x1340B508. All three use the same component transform accessor at RVA 0x107BBB8C and the conditional handler slot at RVA 0x2070B978. The handler currently begins RET. These getters do not supply an independently identified new decoding algorithm. Foreign world-space positions remain unverified.
Current live data limitation: lobby-object-availability.json shows BP_GameState_IrisSafeHouse_C, roster count 1, generic Pawn. Match player objects and actual invocation context are unavailable in this lobby capture. Existing replay uses synthetic context and cannot establish their coordinates.

## Active bone buffer investigation (2026-10-08)

Read-only live disassembly establishes GetBoneTransform RVA 0x10E1628C, active array selector int32 at SkinnedMeshComponent+0x794, array header at +0x750+selector*0x10, transform stride 0x30. A weak master-pose reference at +0x744/+0x748 can redirect this source. Character mesh pointer remains +0x3D0. This supplies component-space transforms, not independent world translation.

The all-loaded-level lobby scan (World.Levels +0x158) found 47 levels, 475 actors, 782 traversed components, 28 skeletal meshes. Character preview meshes held 80 and 75 transforms while CachedBoneSpaceTransforms/+0xA08 and CachedComponentSpaceTransforms/+0xA18 remained empty. A later capture found both active arrays cleared despite same GPSkeletalMeshComponent identities; do not treat this as a continuously populated source. Historical match mesh addresses were invalid or reused (one now GameAkComponent).

GetFootLocation RVA 0xB6D0A98 and Pawn nav-location implementation RVA 0x8D8DFB4 use the already investigated component transform/dispatch path. DFM GetBodyPartLocation reaches named bones but still composes with mesh world transform. No verified foreign world positions or screen alignment resulted. Evidence: alternate-position-targets.json, body-transform-targets.json, bone-storage-trace.json, bone-transform-storage.json, lobby-all-level-active-bones.json, lobby-bone-geometry.json, bone-coordinate-candidate.json. capture_match_active_bones.py is prepared for a fresh match without chasing teammates.

## Live match bounds, batching, and handler table (2026-10-08)

GetActorBounds native body RVA 0x12433CA0 reads component Bounds at +0x148: EncVector center (16 bytes), extent +0x158 (12), sphere radius +0x164 (4). Live bounds captures found plaintext foreign mesh centers, but subsequent DeadInfo.bIsDead (Pawn+0xDC8) and LastIsDead (+0xE35) were 1 for all three remaining plaintext remote meshes. The remaining live ally still had encoded mesh bounds. These plaintext samples cannot establish living player positions.

Page-batched reader capture_batched_player_geometry.py sampled camera/roster/pawn/root/mesh pages in 0.408–0.476 seconds per batch. This reduces timing skew but is not frame-atomic. Latest sample had self alive, three Team4 dead, one Team1 alive. User subsequently confirmed a teammate died, another evacuated, and then left the match.

Adjacent to RET dispatch at 0x7A66E1F140, function 0x7A66E1F148 parses handler indices and uses protected runtime state. State lookup arithmetic resolved 0x7AFEE77000; state resource+0x130 points to libUE4 base. Handler-table headers are libUE4+0x2000BCA8 and +0x2000BCD0, each count4094. Entries stride16 contain vector address, size12, and metadata; handlers select low12-bit index and bit12 bank. Multiple captured entries matched actual vector addresses exactly. Tables identify storage, not decoded coordinates.

Code also selects protected per-vector candidate data and includes a PACGA branch, active flag1 at state+0x339. Do not substitute emulator PAC results or treat synthetic thread context as real key data. Metadata lookup target 0x7A66E6AD94 was locally emulated: initial missing TLS caused a read at0x8; synthetic libc TLS allowed 1067 instructions to return, but result was null. Snapshot pages are non-atomic and may span the transition out of the match. This experiment did not produce decoded coordinates. No new verified world-coordinate contract exists. Evidence: decoded-vector-state.json, vector-records.json, vector-vm-lookup.json, vector-lookup-emulation.json, batched-geometry/*.json.

## Offline lookup audit and payload arithmetic (2026-10-08)

The frozen 1067-instruction lookup trace reaches binary search. Its index page at 0x7B06538000 and record0 page at 0x7735AE3000 are all zero; repeated search indices resolve to zero. Fresh lobby reads confirm these addresses still exist but current runtime record count at state+0x1680+45*4 is0. The snapshot used an older state count (283) with empty backing pages, so its null lookup must not be interpreted as evidence against the native lookup algorithm. No fully coherent match runtime-record snapshot was captured.

Native unpacker at 0x7A66E1FA80 was translated into vector_payload_arithmetic.py. It requires a 12-byte payload, runtime key and runtime mask. verify_vector_payload_native.py executed the captured ARM64 instructions against 64 synthetic cases (32 per mode1/6); all matched the Python arithmetic. This only verifies arithmetic equivalence; actual key and living-player world coordinates remain unresolved. PACGA is present in the key path and synthetic/emulator keys are not device/game keys.

capture_vector_runtime_storage.py now captures the actual record and sorted-index tables with batched read-only pages and before/after header checks, rejecting count0 explicitly. Current run confirms empty_runtime_storage (lobby), and cannot furnish the missing actual match payload/key. Evidence: vector-lookup-offline-audit.json, vector-lookup-storage-check.json, vector-payload-equivalence.json, vector-runtime-captures/*/manifest.json.

## Verified coordinate decoder and fresh-match HUD comparison (2026-10-08)

Resolved process key 0x765D0871 by exhaustive 32-bit search over 16 player records; all 63 held-out records bounded. Native ARM64 payload arithmetic agrees on 79 real captured inputs. Exact native payload-slot formula selects the populated slot for all 79 records. Record hash inversion links handlers to Root.RelativeLocation and Bounds.Center; fresh-match captures decode new player addresses and movement with the same key. Two HUD comparisons give 252.03 m vs 252 m and 169.29 m vs 168 m. Latest living ally identity matches and AttachParent=0; camera compass conversion yaw+90 gives122.91 degrees vs123 degrees on HUD. Horizontal marker agreement is visual, not exact vertical body-box validation. Latest screenshot brackets span3.56 seconds and moved, so timing error remains. Evidence WORLD_COORDINATES_VERIFIED.json, VERIFIED_OFFSETS.md, captured-payload-native-verification.json, current-slot-verification.json and projection-captures/1791478646173444779. Basic world-coordinate path is now established; NPC classification, exact body boxes and world bones are not claimed. Read-only native page helper reduces targeted memory batch to0.10–0.12 seconds.
