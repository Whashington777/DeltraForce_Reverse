# Garena reference comparison

Reference build: com.garena.game.df 1.203.37102.1401. Local build: com.proxima.dfm 1.202.37117.5601.

| Field | Reference | Local reflected |
|---|---|---|
| Actor.RootComponent | 0x180 | 0x180 |
| GameStateBase.PlayerArray | 0x388 | 0x388 |
| PlayerController.PlayerCameraManager | 0x408 | 0x408 |
| Actor.ReplicatedMovement | 0x9C, size 0x34 | 0x9C, size 0x38 |
| RepMovement.Location | 0x18, FVector size 12 | 0x18, EncVector size 16 |
| RepMovement.Rotation | 0x24 | 0x28 |
| SceneComponent.RelativeLocation | 0x164, FVector | 0x168, EncVector |
| MinimalViewInfo.Rotation | 0xC | 0x10 |
| MinimalViewInfo.FOV | 0x18 | 0x1C |
| CameraCacheEntry.POV | 0x10 | 0x10 |
| PlayerCameraManager.CameraCachePrivate | 0x2B60 | 0x2D60 |

The reference uses FVector where the local build uses EncVector. Copying reference coordinate layouts would misread local rotation and FOV. The reference contains no EncHandler decoder and its global World pointer is 0 (not provided).

New leads for local reflection: Character.CharacterMovement (reference 0x3D8), CharacterMovementComponent.LastUpdateLocation (reference 0x2A0), and GPCharacterMovementComponent.MeshTranslationOffset (reference 0xFA4). These are reference offsets only, not validated local positions.
