# Own reflection geometry contract

Validated against earlier independently captured metadata. This checks member layouts; it does not validate world-space coordinates.

| Owner | Field | Offset | Size |
|---|---|---:|---:|
| Actor | RootComponent | 0x180 | 8 |
| Actor | ReplicatedMovement | 0x9c | 56 |
| SceneComponent | RelativeLocation | 0x168 | 16 |
| EncVector | EncHandler | 0xc | 4 |
| RepMovement | Location | 0x18 | 16 |
| RepMovement | Rotation | 0x28 | 12 |
| PlayerController | PlayerCameraManager | 0x408 | 8 |
| PlayerCameraManager | CameraCachePrivate | 0x2d60 | 2640 |
| CameraCacheEntry | POV | 0x10 | 2624 |
| MinimalViewInfo | Rotation | 0x10 | 12 |
| MinimalViewInfo | FOV | 0x1c | 4 |

K2_GetActorLocation native exec RVA: `0x115A16DC`. It reads Actor.RootComponent, obtains its transform, copies translation from transform+0x10 and conditionally calls the dispatch slot at libUE4+0x2070B978. That slot currently points at RET. See getactorlocation-exec.txt for the observed call path.

Remote world position is not validated. Foreign RootComponent/transform values must not be treated as a ready overlay source.

Additional reflected exec RVAs: K2_GetComponentLocation `0x11CF37D8`, K2_GetComponentToWorld `0x1340B508`. Both follow the same conditional handling path as K2_GetActorLocation; see scene-position-function-code.json.
