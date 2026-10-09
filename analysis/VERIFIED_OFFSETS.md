# Delta Force Android: проверенный путь координат

Сборка: com.proxima.dfm 1.202.37117.5601, arm64. Смещения относительно libUE4 или указанного объекта. Адреса процесса и ключ не являются универсальными оффсетами.

| Поле | Смещение |
|---|---|
| libUE4 → World | `0x20AA87A0` |
| World → GameState | `0x140` |
| GameState → PlayerArray / count | `0x388` / `0x390` |
| PlayerState → Pawn | `0x3F8` |
| PlayerState → TeamID | `0x658` |
| Pawn → RootComponent / Mesh | `0x180` / `0x3D0` |
| Pawn → DeadInfo.bIsDead | `0xDC8` |
| RootComponent → AttachParent | `0x108` |
| RootComponent → RelativeLocation, EncVector16 | `0x168` |
| RootComponent / Mesh → Bounds.Center, EncVector16 | `0x148` |
| Bounds → Extent, три float | `0x10` после Center |
| EncVector → handler | `0x0C` |
| World → GameInstance | `0x190` |
| GameInstance → LocalPlayers | `0x38` |
| LocalPlayer → PlayerController | `0x30` |
| PlayerController → PlayerCameraManager | `0x408` |
| PlayerController → ControlRotation | `0x3D8` |
| PlayerCameraManager → private POV Location | `0x2D70` |
| PlayerCameraManager → private POV Rotation / FOV | `0x2D80` / `0x2D8C` |

**Удалённые EncVector нельзя читать как обычные XYZ.** Их сырые значения в проверенных снимках были ложными. `vector_runtime_decoder.py` находит запись по хешу адреса handler, выбирает слот по нативной формуле и расшифровывает 12 байт через `vector_payload_arithmetic.py`.

Для текущего PID 22846: runtime state `0x7AFEE77000`, process key `0x765D0871`, mask `0xFFFFFFFF`. Ключ найден перебором всех 32-битных вариантов на 16 записях игроков; 63 отложенные записи тоже декодировались в допустимые XYZ. Нативный распаковщик совпал с Python на 79 реальных payload; формула выбора слота совпала на 79/79 записях. В новом матче тот же ключ расшифровал новые объекты и движения.

Проверка по HUD: 252.03 м против 252 м на одном кадре; 169.29 м против 168 м на другом. На втором кадре рассчитанный курс 122.91° совпал с 123° на компасе; горизонтальная проекция живого союзника согласовалась с меткой. Его Pawn/PlayerState совпадают, DeadInfo=0, AttachParent=0. Проверка: `WORLD_COORDINATES_VERIFIED.json`.

Для Actor-позиции RelativeLocation применима при AttachParent=0; при прикреплении используйте подтверждённый мировой Bounds.Center либо корректно составляйте трансформы. Bounds.Center отличается от позиции ног. Для базовых боксов есть центр и extents, но точные вертикальные края боксов и мировые кости ещё не проверены по пикселям. Захваты страниц и скриншоты не атомарны.

ARM64-ридер `trace_readpages_arm64` открывает `/proc/PID/mem` с O_RDONLY и выполняет pread. Он не использует ptrace и не записывает в память игры. Быстрый целевой захват занимает около 0.10–0.12 с; скриншот занимает несколько секунд. После перезапуска процесса ключ и runtime-адреса требуют повторного определения.
