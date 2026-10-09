# Own reflection fields

Type membership checked. Coordinate values remain unverified.

## AILabCharacterDebugInfoBunch

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DebugInfoBunch | 0x0 | 16 |  |

## AIRequestID

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| requestId | 0x0 | 4 |  |

## AOReplacingSourcePrimitiveData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Primitive | 0x0 | 40 | PrimitiveComponent |
| Sections | 0x28 | 16 |  |
| PrimitiveWeight | 0x38 | 4 | AnimNotifyTrack |

## AOReplacingSourceSection

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ItemIndex | 0x0 | 4 | BPVariableDescription |
| Weight | 0x4 | 4 | AOReplacingSourcePrimitiveData |

## AbilityItemOutLineData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ItemUin | 0x0 | 4 |  |
| ItemOutLineType | 0x4 | 4 | EAbilityItemOutLineType |
| TeamOrCampID | 0x8 | 4 | AbilityItemOutLineData |
| OutlineEndTime | 0xc | 4 |  |

## AbilityKnockbackSettingConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| HeightCurve | 0x0 | 8 | CurveFloat |
| MovePath | 0x8 | 8 | CurveFloat |
| RotLerpTime | 0x10 | 4 | AbilityKnockbackSettingConfig |
| bNeedStand | 0x14 | 1 |  |
| KnockDownTime | 0x18 | 4 | AbilityKnockbackSettingConfig |
| GetUpTime | 0x1c | 4 | AbilityKnockbackSettingConfig |
| InitZSpped | 0x20 | 4 | AbilityKnockbackSettingConfig |
| BlendInTime | 0x24 | 4 | AbilityKnockbackSettingConfig |
| BlendOutTime | 0x28 | 4 | AbilityKnockbackSettingConfig |
| GravityZ | 0x2c | 4 | AbilityKnockbackSettingConfig |
| CheckFallingTime | 0x30 | 4 | AbilityKnockbackSettingConfig |
| bForceRotateImmediate | 0x34 | 1 |  |
| FallingVelocityDecelerate | 0x38 | 4 | AbilityKnockbackSettingConfig |
| KnockBackBodyLength | 0x3c | 4 | AbilityKnockbackSettingConfig |
| KnockBackDownTime | 0x40 | 4 | AbilityKnockbackSettingConfig |
| EnterPostProcessName | 0x44 | 8 | AbilityKnockbackSettingConfig |
| DisableCrouchInSimulation | 0x4c | 1 |  |
| bUseFullBodyAllOverride | 0x4d | 1 |  |
| SimulationAnimLoopAddTime | 0x50 | 4 | MarkerViewCreateConfig |
| RoleLoadConfigArray | 0x58 | 16 |  |
| FallingAttackValueId | 0x68 | 4 | AbilityKnockbackSettingConfig |
| GetUpEvent | 0x6c | 8 | AbilityKnockbackSettingConfig |
| FallDownTime | 0x74 | 4 |  |
| FallDownFootSoundType | 0x78 | 1 | EGPAudioFootSoundType |
| AddBuffs | 0x80 | 16 |  |
| DefaultFallDownTime | 0x90 | 4 | AbilityKnockbackSettingConfig |
| ForceResetMoveMode | 0x94 | 1 |  |
| RollSetupRevertDistance | 0x98 | 4 | AbilityKnockbackSettingConfig |
| RollRevertAngle | 0x9c | 4 | AbilityKnockbackSettingConfig |
| EnterWaterEffectOnWaterOffset | 0xa0 | 4 | AbilityKnockbackSettingConfig |
| EnterWaterStartEffectOnWaterOffset | 0xa4 | 4 | AbilityKnockbackSettingConfig |
| DiveIntoWaterOffset | 0xa8 | 4 | AbilityKnockbackSettingConfig |
| InToWaterInteractionName | 0xac | 8 |  |

## ActiveGameplayEffect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Spec | 0x18 | 664 | GameplayEffectSpec |
| PredictionKey | 0x2b0 | 24 | PredictionKey |
| StartServerWorldTime | 0x2c8 | 4 | ActiveGameplayEffect |
| CachedStartServerWorldTime | 0x2cc | 4 | ActiveGameplayEffect |
| StartWorldTime | 0x2d0 | 4 | FastArraySerializerItem |
| bIsInhibited | 0x2d4 | 1 |  |

## Actor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PrimaryActorTick | 0x28 | 104 | ActorTickFunction |
| bHidden | 0x90 | 1 |  |
| bEnableNetActive | 0x90 | 1 |  |
| bNetActive | 0x90 | 1 |  |
| bNetTemporary | 0x90 | 1 |  |
| bNetStartup | 0x90 | 1 |  |
| bOnlyRelevantToOwner | 0x90 | 1 |  |
| bAlwaysRelevant | 0x90 | 1 |  |
| bReplicateMovement | 0x90 | 1 |  |
| bShouldCallPreReplication | 0x91 | 1 |  |
| bTearOff | 0x91 | 1 |  |
| bExchangedRoles | 0x91 | 1 |  |
| bNetLoadOnClient | 0x91 | 1 |  |
| bNetUseOwnerRelevancy | 0x91 | 1 |  |
| bRelevantForNetworkReplays | 0x91 | 1 |  |
| bRelevantForLevelBounds | 0x91 | 1 |  |
| bReplayRewindable | 0x92 | 1 |  |
| bAllowTickBeforeBeginPlay | 0x92 | 1 |  |
| bAllowBluePrintTick | 0x92 | 1 |  |
| bAutoDestroyWhenFinished | 0x92 | 1 |  |
| bBlockInput | 0x92 | 1 |  |
| bCanBeDamaged | 0x92 | 1 |  |
| bCollideWhenPlacing | 0x92 | 1 |  |
| bFindCameraComponentWhenViewTarget | 0x92 | 1 |  |
| bGenerateOverlapEventsDuringLevelStreaming | 0x93 | 1 |  |
| bIgnoresOriginShifting | 0x93 | 1 |  |
| bEnableAutoLODGeneration | 0x93 | 1 |  |
| bIsEditorOnlyActor | 0x93 | 1 |  |
| bActorSeamlessTraveled | 0x93 | 1 |  |
| bReplicates | 0x93 | 1 |  |
| bCanBeInCluster | 0x93 | 1 |  |
| bAllowReceiveTickEventOnDedicatedServer | 0x93 | 1 |  |
| bActorEnableCollision | 0x95 | 1 |  |
| bActorIsBeingDestroyed | 0x95 | 1 |  |
| UpdateOverlapsMethodDuringLevelStreaming | 0x96 | 1 | EActorUpdateOverlapsMethod |
| DefaultUpdateOverlapsMethodDuringLevelStreaming | 0x97 | 1 | EActorUpdateOverlapsMethod |
| RemoteRole | 0x98 | 1 | ENetRole |
| ReplicatedMovement | 0x9c | 56 | RepMovement |
| InitialLifeSpan | 0xd4 | 4 | Actor |
| CustomTimeDilation | 0xd8 | 4 | RepAttachment |
| AttachmentReplication | 0xe0 | 64 | RepAttachment |
| Owner | 0x120 | 8 | Actor |
| NetDriverName | 0x128 | 8 | Actor |
| Role | 0x130 | 1 | ENetRole |
| NetDormancy | 0x131 | 1 | ENetDormancy |
| SpawnCollisionHandlingMethod | 0x132 | 1 | ESpawnActorCollisionHandlingMethod |
| AutoReceiveInput | 0x133 | 1 | EAutoReceiveInput |
| InputPriority | 0x134 | 4 | GPSequenceMultiStageActor |
| InputComponent | 0x138 | 8 | InputComponent |
| NetCullDistanceSquared | 0x140 | 4 | Actor |
| NetCullDistanceSquared_HD | 0x144 | 4 | Actor |
| NetCullDistanceSquared_M | 0x148 | 4 | Actor |
| NetTag | 0x14c | 4 | Actor |
| NetUpdateFrequency | 0x150 | 4 | Actor |
| MinNetUpdateFrequency | 0x154 | 4 | Actor |
| NetPriority | 0x158 | 4 |  |
| Instigator | 0x168 | 8 | Pawn |
| Children | 0x170 | 16 |  |
| RootComponent | 0x180 | 8 | SceneComponent |
| ControllingMatineeActors | 0x188 | 16 |  |
| Layers | 0x1a0 | 16 |  |
| ParentComponent | 0x1b0 | 8 | ChildActorComponent |
| Tags | 0x1b8 | 16 |  |
| OnTakeAnyDamage | 0x1c8 | 1 |  |
| OnTakePointDamage | 0x1c9 | 1 |  |
| OnTakeRadialDamage | 0x1ca | 1 |  |
| OnActorBeginOverlap | 0x1cb | 1 |  |
| OnActorEndOverlap | 0x1cc | 1 |  |
| OnBeginCursorOver | 0x1cd | 1 |  |
| OnEndCursorOver | 0x1ce | 1 |  |
| OnClicked | 0x1cf | 1 |  |
| OnReleased | 0x1d0 | 1 |  |
| OnInputTouchBegin | 0x1d1 | 1 |  |
| OnInputTouchEnd | 0x1d2 | 1 |  |
| OnInputTouchEnter | 0x1d3 | 1 |  |
| OnInputTouchLeave | 0x1d4 | 1 |  |
| OnActorHit | 0x1d5 | 1 |  |
| OnDestroyed | 0x1f8 | 1 |  |
| OnEndPlay | 0x1f9 | 1 |  |
| InstanceComponents | 0x270 | 16 |  |
| BlueprintCreatedComponents | 0x280 | 16 |  |

## ActorComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PrimaryComponentTick | 0x30 | 104 | ActorComponentTickFunction |
| ComponentTags | 0x98 | 16 |  |
| bAllowBluePrintTick | 0xa8 | 1 |  |
| AssetUserData | 0xb0 | 16 |  |
| bReplicates | 0xc8 | 1 |  |
| bShouldCallPreReplication | 0xc8 | 1 |  |
| bNetAddressable | 0xc8 | 1 |  |
| bRegisterAsData | 0xc8 | 1 |  |
| ReplicationFlag | 0xca | 1 | EComponentReplicationFlags |
| bAutoActivate | 0xcb | 1 |  |
| bIsActive | 0xcb | 1 |  |
| bEditableWhenInherited | 0xcb | 1 |  |
| bCanEverAffectNavigation | 0xcc | 1 |  |
| bIsEditorOnly | 0xcc | 1 |  |
| CreationMethod | 0xce | 1 | EComponentCreationMethod |
| OnComponentActivated | 0xcf | 1 |  |
| OnComponentDeactivated | 0xd0 | 1 |  |
| UCSModifiedProperties | 0xd8 | 16 |  |

## ActorComponentInstanceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SourceComponentTemplate | 0x8 | 8 | Object |
| SourceComponentCreationMethod | 0x10 | 1 | EComponentCreationMethod |
| SourceComponentTypeSerializedIndex | 0x14 | 4 |  |
| SavedProperties | 0x18 | 16 |  |
| DuplicatedObjects | 0x28 | 16 |  |
| ReferencedObjects | 0x38 | 16 |  |
| ReferencedNames | 0x48 | 16 |  |

## ActorMoveMessage

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Position | 0x0 | 12 | Vector |
| Rotation | 0xc | 12 | Rotator |
| Velocity | 0x18 | 12 | Vector |
| ClientTick | 0x24 | 4 | GPCharacterBase |
| Snapshot | 0x28 | 1 |  |

## ActorTickFunction

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## AdditionalPRTMarker

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DataMap | 0x0 | 80 |  |

## AllPlayerLoadLevelCompletedInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CheckLoadLevelReason | 0x0 | 8 | DSTickInfo |
| HasAllPlayerLoadLevelCompleted | 0x8 | 1 |  |

## AmmoContext

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AmmoDataItems | 0x0 | 16 |  |

## AmmoDataItem

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ItemID | 0x0 | 8 | AmmoDataItem |
| Guid | 0x8 | 8 | AmmoDataItem |
| Num | 0x10 | 4 |  |
| BindPlayerId | 0x18 | 8 |  |
| ContainPlayerIds | 0x20 | 16 |  |
| bSubClip | 0x30 | 1 |  |
| CooledNumTaken | 0x34 | 4 | OverHeatContext |

## AnchorData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Offsets | 0x0 | 16 | Margin |
| Anchors | 0x10 | 16 | Anchors |
| Alignment | 0x20 | 8 | Vector2D |

## Anchors

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Minimum | 0x0 | 8 | Vector2D |
| Maximum | 0x8 | 8 | Vector2D |

## AngularDriveConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TwistDrive | 0x0 | 16 | ConstraintDrive |
| SwingDrive | 0x10 | 16 | ConstraintDrive |
| SlerpDrive | 0x20 | 16 | ConstraintDrive |
| OrientationTarget | 0x30 | 12 | Rotator |
| AngularVelocityTarget | 0x3c | 12 | Vector |
| AngularDriveMode | 0x48 | 1 | EAngularDriveMode |

## AnimInstanceProxy

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SkeletalMeshComponent | 0xb8 | 8 | SkeletalMeshComponent |

## AnimNotifyTrack

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TrackName | 0x0 | 8 | AnimSyncMarker |
| TrackColor | 0x8 | 16 | LinearColor |

## AnimRootMotionInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Anim | 0x0 | 8 | AnimMontage |
| PlayRateOveride | 0x8 | 4 | MotionCorrectionSection |
| AnimTransform | 0x10 | 48 | Transform |
| MotionCorrectionInfo | 0x40 | 96 | MotionCorrectionInfo |
| AnimStartTime | 0xa0 | 4 | AnimRootMotionInfo |
| AnimEndTime | 0xa4 | 4 | AnimRootMotionInfo |
| StartFrame | 0xa8 | 4 | AnimRootMotionInfo |
| EndFrame | 0xac | 4 | MotionActionExtParam |
| ExtParams | 0xb0 | 16 | MotionActionExtParams |
| bAtomic | 0xc0 | 1 |  |

## AnimSlotInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SlotName | 0x0 | 8 |  |
| ChannelWeights | 0x8 | 16 |  |

## AnimSyncMarker

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkerName | 0x0 | 8 | AnimSyncMarker |
| Time | 0x8 | 4 | TrackToSkeletonMap |

## AnimUpdateRateParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ShiftBucket | 0x1 | 1 | EUpdateRateShiftBucket |
| bInterpolateSkippedFrames | 0x2 | 1 |  |
| bShouldUseLodMap | 0x2 | 1 |  |
| bShouldUseMinLod | 0x2 | 1 |  |
| bShouldUseMinURO | 0x2 | 1 |  |
| bSkipUpdate | 0x2 | 1 |  |
| bSkipEvaluation | 0x2 | 1 |  |
| UpdateRate | 0x4 | 4 | AnimUpdateRateParameters |
| EvaluationRate | 0x8 | 4 | PredictProjectilePathPointData |
| TickedPoseOffestTime | 0xc | 4 | AnimUpdateRateParameters |
| AdditionalTime | 0x10 | 4 | AnimUpdateRateParameters |
| BaseNonRenderedUpdateRate | 0x18 | 4 | AnimUpdateRateParameters |
| MaxEvalRateForInterpolation | 0x1c | 4 |  |
| BaseVisibleDistanceFactorThesholds | 0x20 | 16 |  |
| LODToFrameSkipMap | 0x30 | 80 |  |
| BaseVisibleDistanceFactorThesholdsRates | 0x80 | 16 |  |
| SkippedUpdateFrames | 0x98 | 4 | AnimUpdateRateParameters |
| SkippedEvalFrames | 0x9c | 4 | POV |

## AnimationState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Transitions | 0x8 | 16 |  |
| StateRootNodeIndex | 0x18 | 4 | AnimationState |
| StartNotify | 0x1c | 4 | AnimationState |
| EndNotify | 0x20 | 4 | AnimationState |
| FullyBlendedNotify | 0x24 | 4 | BakedAnimationStateMachine |

## AnimationStateBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StateName | 0x0 | 8 | InteriorSettings |

## AnimationTransitionRule

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| RuleToExecute | 0x0 | 8 | AnimationTransitionRule |
| TransitionReturnVal | 0x8 | 1 |  |
| TransitionIndex | 0xc | 4 | AnimationState |

## AssetManagerRedirect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| old | 0x0 | 16 | AssetManagerRedirect |
| New | 0x10 | 16 | PrimaryAssetRulesCustomOverride |

## AtmospherePrecomputeParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DensityHeight | 0x0 | 4 | AtmospherePrecomputeParameters |
| DecayHeight | 0x4 | 4 | AtmospherePrecomputeParameters |
| MaxScatteringOrder | 0x8 | 4 | AtmospherePrecomputeParameters |
| TransmittanceTexWidth | 0xc | 4 | AtmospherePrecomputeParameters |
| TransmittanceTexHeight | 0x10 | 4 | AtmospherePrecomputeParameters |
| IrradianceTexWidth | 0x14 | 4 | AtmospherePrecomputeParameters |
| IrradianceTexHeight | 0x18 | 4 | AtmospherePrecomputeParameters |
| InscatterAltitudeSampleNum | 0x1c | 4 | AtmospherePrecomputeParameters |
| InscatterMuNum | 0x20 | 4 | AtmospherePrecomputeParameters |
| InscatterMuSNum | 0x24 | 4 | AtmospherePrecomputeParameters |
| InscatterNuNum | 0x28 | 4 | PrimaryAssetTypeInfo |

## AudioComponentParam

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ParamName | 0x0 | 8 | AudioComponentParam |
| FloatParam | 0x8 | 4 | AudioComponentParam |
| BoolParam | 0xc | 1 |  |
| IntParam | 0x10 | 4 | BaseAttenuationSettings |
| SoundWaveParam | 0x18 | 8 | SoundWave |

## AudioEQEffect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FrequencyCenter0 | 0x8 | 4 | AudioEQEffect |
| Gain0 | 0xc | 4 | AudioEQEffect |
| Bandwidth0 | 0x10 | 4 | AudioEQEffect |
| FrequencyCenter1 | 0x14 | 4 | AudioEQEffect |
| Gain1 | 0x18 | 4 | AudioEQEffect |
| Bandwidth1 | 0x1c | 4 | AudioEQEffect |
| FrequencyCenter2 | 0x20 | 4 | AudioEQEffect |
| Gain2 | 0x24 | 4 | AudioEQEffect |
| Bandwidth2 | 0x28 | 4 | AudioEQEffect |
| FrequencyCenter3 | 0x2c | 4 | AudioEQEffect |
| Gain3 | 0x30 | 4 | AudioEQEffect |
| Bandwidth3 | 0x34 | 4 | SoundClassAdjuster |

## AudioQualitySettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DisplayName | 0x0 | 24 | AudioQualitySettings |
| MaxChannels | 0x18 | 4 | AudioComponentParam |

## AutoCompleteNode

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| IndexChar | 0x0 | 4 |  |
| AutoCompleteListIndices | 0x8 | 16 |  |

## AutomationEvent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Type | 0x0 | 1 | EAutomationEventType |
| Message | 0x8 | 16 |  |
| Context | 0x18 | 16 | PolyglotTextData |
| Artifact | 0x28 | 16 | Guid |

## AutomationExecutionEntry

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Event | 0x0 | 56 | AutomationEvent |
| Filename | 0x38 | 16 | AutomationExecutionEntry |
| LineNumber | 0x48 | 4 | AutomationEvent |
| Timestamp | 0x50 | 8 | DateTime |

## BPEditorBookmarkNode

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| NodeGuid | 0x0 | 16 | Guid |
| ParentGuid | 0x10 | 16 | Guid |
| DisplayName | 0x20 | 24 | InterpolationParameter |

## BPVariableDescription

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| VarName | 0x0 | 8 | BPVariableDescription |
| VarGuid | 0x8 | 16 | Guid |
| VarType | 0x18 | 88 | EdGraphPinType |
| FriendlyName | 0x70 | 16 | PostProcessSettings |
| Category | 0x80 | 24 | BPVariableDescription |
| PropertyFlags | 0x98 | 8 | BPVariableDescription |
| RepNotifyFunc | 0xa0 | 8 | BPVariableMetaDataEntry |
| ReplicationCondition | 0xa8 | 1 | ELifetimeCondition |
| MetaDataArray | 0xb0 | 16 |  |
| DefaultValue | 0xc0 | 16 | EditedDocumentInfo |

## BPVariableMetaDataEntry

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DataKey | 0x0 | 8 | BPVariableMetaDataEntry |
| DataValue | 0x8 | 16 | BPVariableDescription |

## BP_GameState_IrisSafeHouse_C

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BP_SOLInteractSystemBase | 0x1090 | 8 | BP_SOLInteractSystemBase_C |
| BP_InteractSystemComponent_IrisSafeHouse | 0x1098 | 8 | BP_InteractSystemComponent_IrisSafeHouse_C |
| DefaultSceneRoot | 0x10a0 | 8 | SceneComponent |

## BP_SafeHousePlayerController_C

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| UberGraphFrame | 0xe80 | 8 | PointerToUberGraphFrame |
| DFMControllerAudio | 0xe88 | 8 | DFMControllerAudioComponent |
| DFMQuestGamingAreaPlayer | 0xe90 | 8 | DFMQuestGamingAreaPlayerComponent |
| SimulationLODPerception | 0xe98 | 8 | SimulationLODPerceptionComponent |
| MiniManTransform | 0xea0 | 48 | Transform |
| MiniManActor | 0xed0 | 8 | Object |
| bOpenAIDebug | 0xed8 | 1 |  |

## BP_TestPlayerCameraManager_C

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CameraTrans | 0x5590 | 8 | CameraTransComponent |
| bDebugPPS | 0x5598 | 1 |  |

## BakedAnimationState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StateName | 0x0 | 8 | BakedStateExitTransition |
| Transitions | 0x8 | 16 |  |
| StateRootNodeIndex | 0x18 | 4 | BakedAnimationState |
| StartNotify | 0x1c | 4 | BakedAnimationState |
| EndNotify | 0x20 | 4 | BakedAnimationState |
| FullyBlendedNotify | 0x24 | 4 | BakedAnimationState |
| bIsAConduit | 0x28 | 1 |  |
| EntryRuleNodeIndex | 0x2c | 4 |  |
| PlayerNodeIndices | 0x30 | 16 |  |
| LayerNodeIndices | 0x40 | 16 |  |
| bAlwaysResetOnEntry | 0x50 | 1 |  |
| bLoopState | 0x51 | 1 |  |

## BakedAnimationStateMachine

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MachineName | 0x0 | 8 | BakedAnimationStateMachine |
| InitialState | 0x8 | 4 | BakedAnimationState |
| States | 0x10 | 16 |  |
| Transitions | 0x20 | 16 |  |

## BakedStateExitTransition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CanTakeDelegateIndex | 0x0 | 4 | BakedStateExitTransition |
| CustomResultNodeIndex | 0x4 | 4 | BakedStateExitTransition |
| TransitionIndex | 0x8 | 4 |  |
| bDesiredTransitionReturnValue | 0xc | 1 |  |
| bAutomaticRemainingTimeRule | 0xd | 1 |  |
| PoseEvaluatorLinks | 0x10 | 16 |  |

## BaseAttenuationSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DistanceAlgorithm | 0x8 | 1 | EAttenuationDistanceModel |
| AttenuationShape | 0x9 | 1 | EAttenuationShape |
| dBAttenuationAtMax | 0xc | 4 | BaseAttenuationSettings |
| AttenuationShapeExtents | 0x10 | 12 | Vector |
| ConeOffset | 0x1c | 4 | BaseAttenuationSettings |
| FalloffDistance | 0x20 | 4 | AtmospherePrecomputeParameters |
| CustomAttenuationCurve | 0x28 | 160 | RuntimeFloatCurve |

## BaseDOFConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FocalDistance | 0x0 | 4 | BaseDOFConfig |
| FocalRegion | 0x4 | 4 | BaseDOFConfig |
| NearTransitionRegion | 0x8 | 4 | BaseDOFConfig |
| FarTransitionRegion | 0xc | 4 | PhysicalCameraConfig |

## BaseGameState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GameStartTime | 0x3d0 | 4 | GameState |

## BasePlayerController

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## BasedMovementInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MovementBase | 0x0 | 8 | PrimitiveComponent |
| BoneName | 0x8 | 8 | CHARACTER |
| Location | 0x10 | 12 | Vector_NetQuantize100 |
| Rotation | 0x1c | 12 | Rotator |
| bServerHasBaseComponent | 0x28 | 1 |  |
| bRelativeRotation | 0x29 | 1 |  |
| bServerHasVelocity | 0x2a | 1 |  |

## BasicData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## BatchedLine

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Start | 0x0 | 12 | Vector |
| End | 0xc | 12 | Vector |
| Color | 0x18 | 16 | LinearColor |
| Thickness | 0x28 | 4 | BatchedLine |
| RemainingLifeTime | 0x2c | 4 | BatchedPoint |
| DepthPriority | 0x30 | 1 |  |

## BatchedPoint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Position | 0x0 | 12 | Vector |
| Color | 0xc | 16 | LinearColor |
| PointSize | 0x1c | 4 | BatchedPoint |
| RemainingLifeTime | 0x20 | 4 | LightImportanceAssetData |
| DepthPriority | 0x24 | 1 |  |

## BattleFieldMarkingConfigRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkingTagName | 0x10 | 8 | BattleFieldMarkingInfo |
| MarkingInfoMap | 0x18 | 80 |  |

## BattleFieldMarkingInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SelfMarkingCountLimit | 0x0 | 4 | BattleFieldMarkingInfo |
| MarkDistance | 0x4 | 4 | BattleFieldMarkingInfo |
| MarkingMarkerAimCheckRadius | 0x8 | 4 |  |
| MarkingExpandScalarCurve | 0x10 | 8 | CurveFloat |
| MarkingConfigDataMap | 0x18 | 80 |  |

## BattleFieldMarkingViewInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bCanMark | 0x0 | 1 |  |
| MarkingTime | 0x4 | 4 | BattleFieldMarkingViewInfo |
| MarkingVO | 0x8 | 8 | BattleFieldMarkingViewInfo |
| QuickChatText | 0x10 | 24 | BattleFieldMarkingConfigRow |

## BeamTargetData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TargetName | 0x0 | 8 | BeamTargetData |
| TargetPercentage | 0x8 | 4 | EmitterDynamicParameter |

## BlendParameter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DisplayName | 0x0 | 16 | BlendParameter |
| Min | 0x10 | 4 | BlendParameter |
| Max | 0x14 | 4 | BlendParameter |
| GridNum | 0x18 | 4 | BlendSample |

## BlendProfileBoneEntry

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BoneReference | 0x0 | 16 | BoneReference |
| BlendScale | 0x10 | 4 | ExternalToolDefinition |

## BlendSample

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Animation | 0x0 | 8 | AnimSequence |
| SampleValue | 0x8 | 12 | Vector |
| RateScale | 0x14 | 4 | EditorElement |

## BlueprintComponentDelegateBinding

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ComponentPropertyName | 0x0 | 8 | BlueprintComponentDelegateBinding |
| DelegatePropertyName | 0x8 | 8 | BlueprintComponentDelegateBinding |
| FunctionNameToBind | 0x10 | 8 | CollisionResponseTemplate |

## BoneReference

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BoneName | 0x0 | 8 |  |

## Box2D

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Min | 0x0 | 8 | Vector2D |
| Max | 0x8 | 8 | Vector2D |
| bIsValid | 0x10 | 1 |  |

## BoxSphereBounds

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Origin | 0x0 | 12 | Vector |
| BoxExtent | 0xc | 12 | Vector |
| SphereRadius | 0x18 | 4 | LinearColor |

## BreakThroughTacticalMarkingRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkingTagName | 0x10 | 8 | MarkerCampTeamId |
| IdentityAvailableTacticalMarkingTypes | 0x18 | 80 |  |

## BuildPromotionNewProjectSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| NewProjectFolderOverride | 0x0 | 16 | DirectoryPath |
| NewProjectNameOverride | 0x10 | 16 | EditorMapPerformanceTestDefinition |

## CHARACTER

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Mesh | 0x3d0 | 8 | SkeletalMeshComponent |
| CharacterMovement | 0x3d8 | 8 | CharacterMovementComponent |
| CapsuleComponent | 0x3e0 | 8 | CapsuleComponent |
| BasedMovement | 0x3e8 | 48 | BasedMovementInfo |
| ReplicatedBasedMovement | 0x418 | 48 | BasedMovementInfo |
| AnimRootMotionTranslationScale | 0x448 | 4 | CHARACTER |
| BaseTranslationOffset | 0x44c | 12 | Vector |
| BaseRotationOffset | 0x460 | 16 | Quat |
| ReplicatedServerLastTransformUpdateTimeStamp | 0x470 | 4 | CHARACTER |
| ReplayLastTransformUpdateTimeStamp | 0x474 | 4 | CHARACTER |
| ReplicatedMovementMode | 0x478 | 1 |  |
| bInBaseReplication | 0x479 | 1 |  |
| CrouchedEyeHeight | 0x47c | 4 | CHARACTER |
| bIsCrouched | 0x480 | 1 |  |
| bProxyIsJumpForceApplied | 0x480 | 1 |  |
| bPressedJump | 0x480 | 1 |  |
| bClientUpdating | 0x480 | 1 |  |
| bClientWasFalling | 0x480 | 1 |  |
| bClientResimulateRootMotion | 0x480 | 1 |  |
| bClientResimulateRootMotionSources | 0x480 | 1 |  |
| bSimGravityDisabled | 0x480 | 1 |  |
| bClientCheckEncroachmentOnNetUpdate | 0x481 | 1 |  |
| bServerMoveIgnoreRootMotion | 0x481 | 1 |  |
| bWasJumping | 0x481 | 1 |  |
| JumpKeyHoldTime | 0x484 | 4 | CHARACTER |
| JumpForceTimeRemaining | 0x488 | 4 | CHARACTER |
| ProxyJumpForceStartedTime | 0x48c | 4 | CHARACTER |
| JumpMaxHoldTime | 0x490 | 4 | CHARACTER |
| JumpMaxCount | 0x494 | 4 | CHARACTER |
| JumpCurrentCount | 0x498 | 4 | RootMotionMovementParams |
| OnReachedJumpApex | 0x4a0 | 16 |  |
| MovementModeChangedDelegate | 0x4c0 | 16 |  |
| OnCharacterMovementUpdated | 0x4d0 | 16 |  |
| SavedRootMotion | 0x4e0 | 248 | RootMotionSourceGroup |
| ClientRootMotionParams | 0x5e0 | 64 | RootMotionMovementParams |
| RootMotionRepMoves | 0x620 | 16 |  |
| RepRootMotion | 0x630 | 344 | RepRootMotionMontage |

## CachedAnimAssetPlayerData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StateMachineName | 0x0 | 8 | CachedAnimAssetPlayerData |
| StateName | 0x8 | 8 | PostProcessSettings |

## CachedAnimRelevancyData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StateMachineName | 0x0 | 8 | CachedAnimRelevancyData |
| StateName | 0x8 | 8 | CachedAnimTransitionData |

## CachedAnimStateData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StateMachineName | 0x0 | 8 | CachedAnimStateData |
| StateName | 0x8 | 8 | CachedAnimAssetPlayerData |

## CachedAnimTransitionData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StateMachineName | 0x0 | 8 | CachedAnimTransitionData |
| FromStateName | 0x8 | 8 | CachedAnimTransitionData |
| ToStateName | 0x10 | 8 |  |

## CameraCacheEntry

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Timestamp | 0x0 | 4 | PhysicalSurfaceName |
| POV | 0x10 | 2624 | MinimalViewInfo |

## CameraExposureSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Method | 0x0 | 1 | EAutoExposureMethod |
| LowPercent | 0x4 | 4 | CameraExposureSettings |
| HighPercent | 0x8 | 4 | CameraExposureSettings |
| MinBrightness | 0xc | 4 | CameraExposureSettings |
| MaxBrightness | 0x10 | 4 | CameraExposureSettings |
| SpeedUp | 0x14 | 4 | CameraExposureSettings |
| SpeedDown | 0x18 | 4 | CameraExposureSettings |
| Bias | 0x1c | 4 | CameraExposureSettings |
| BiasCurve | 0x20 | 8 | CurveFloat |
| MeterMask | 0x28 | 8 | Texture |
| HistogramLogMin | 0x30 | 4 | CameraExposureSettings |
| HistogramLogMax | 0x34 | 4 | CameraExposureSettings |
| CalibrationConstant | 0x38 | 4 | SVTIntVector4 |
| ApplyPhysicalCameraExposure | 0x3c | 1 |  |

## CameraXppChangeConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FppToTppDuration | 0x0 | 4 | CameraXppChangeConfig |
| FppToTppLocationCurve | 0x8 | 8 | CurveFloat |
| FppToTppRotationCurve | 0x10 | 8 | CurveFloat |
| FppToTppFovCurve | 0x18 | 8 | CurveFloat |
| TppToFppDuration | 0x20 | 4 | SimpleMinimalViewInfo |
| TppToFppLocationCurve | 0x28 | 8 | CurveFloat |
| TppToFppRotationCurve | 0x30 | 8 | CurveFloat |
| TppToFppFovCurve | 0x38 | 8 | CurveFloat |

## CanvasIcon

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Texture | 0x0 | 8 | Texture |
| U | 0x8 | 4 | CanvasIcon |
| V | 0xc | 4 | CanvasIcon |
| UL | 0x10 | 4 | CanvasIcon |
| VL | 0x14 | 4 | MinimalViewInfo |

## CapsuleShape

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Center | 0x0 | 12 | Vector |
| radius | 0xc | 4 | CapsuleShape |
| orientation | 0x10 | 12 | Vector |
| Length | 0x1c | 4 | Sphere |

## CartesianAxisRange

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Min | 0x0 | 4 | CartesianAxisRange |
| Max | 0x4 | 4 | CartesianRangeBound |

## CartesianRangeBound

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Type | 0x0 | 1 | ECartesianRangeBoundType |
| FixedBoundValue | 0x4 | 4 |  |

## CategoryStyleManualMapping

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CategoryId | 0x0 | 8 | SeriesStyleManualMapping |
| Style | 0x8 | 24 | KantanCategoryStyle |

## ChannelDefinition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ChannelName | 0x0 | 8 | ChannelDefinition |
| ClassName | 0x8 | 8 | ChannelDefinition |
| ChannelClass | 0x10 | 8 | Class |
| StaticChannelIndex | 0x18 | 4 | NavigationLinkBase |
| bTickOnCreate | 0x1c | 1 |  |
| bServerOpen | 0x1d | 1 |  |
| bClientOpen | 0x1e | 1 |  |
| bInitialServer | 0x1f | 1 |  |
| bInitialClient | 0x20 | 1 |  |

## CharMarkerData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Active | 0x0 | 1 |  |
| OwnerCampID | 0x4 | 4 | CharMarkerData |
| OwnerTeamID | 0x8 | 4 |  |
| OwnerUin | 0x10 | 8 | GPCharacterBase |

## CharOutLineEffectData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DataIndex | 0x0 | 4 | CharOutLineEffectData |
| OutLineEffectBitArry | 0x8 | 8 | CharOutLineEffectData |
| MarkSources | 0x10 | 16 |  |
| MarkerTipName | 0x20 | 8 |  |

## CharacterBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FPPMesh | 0xaa8 | 8 | SkeletalMeshComponent |
| FPPMeshLowBody | 0xab0 | 8 | SkeletalMeshComponent |
| AllMesh | 0xab8 | 16 |  |

## CharacterControlledActorInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ControlledActor | 0x0 | 8 | Actor |
| bIsControlledActorValid | 0x8 | 1 |  |
| CorrespondingViewTargetBeforeControlled | 0x10 | 8 | Actor |
| ControlledId | 0x18 | 4 |  |

## CharacterMoveHandle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Index | 0x0 | 4 | WeaponFireMulticastInfo |

## CharacterMovementComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CharacterOwner | 0x190 | 8 | CHARACTER |
| GravityScale | 0x198 | 4 | CharacterMovementComponent |
| MaxStepHeight | 0x19c | 4 | CharacterMovementComponent |
| JumpZVelocity | 0x1a0 | 4 | CharacterMovementComponent |
| JumpOffJumpZFactor | 0x1a4 | 4 | CharacterMovementComponent |
| WalkableFloorAngle | 0x1b0 | 4 | CharacterMovementComponent |
| WalkableFloorZ | 0x1b4 | 4 | CharacterMovementComponent |
| MovementMode | 0x1b8 | 1 | EMovementMode |
| CustomMovementMode | 0x1b9 | 1 |  |
| NetworkSmoothingMode | 0x1ba | 1 | ENetworkSmoothingMode |
| GroundFriction | 0x1bc | 4 | CharacterMovementComponent |
| MaxWalkSpeed | 0x1dc | 4 | CharacterMovementComponent |
| MaxWalkSpeedCrouched | 0x1e0 | 4 | CharacterMovementComponent |
| MaxSwimSpeed | 0x1e4 | 4 | CharacterMovementComponent |
| MaxFlySpeed | 0x1e8 | 4 | CharacterMovementComponent |
| MaxCustomMovementSpeed | 0x1ec | 4 | CharacterMovementComponent |
| MaxAcceleration | 0x1f0 | 4 | CharacterMovementComponent |
| MinAnalogWalkSpeed | 0x1f4 | 4 | CharacterMovementComponent |
| BrakingFrictionFactor | 0x1f8 | 4 | CharacterMovementComponent |
| BrakingFriction | 0x1fc | 4 | CharacterMovementComponent |
| BrakingSubStepTime | 0x200 | 4 | CharacterMovementComponent |
| BrakingDecelerationWalking | 0x204 | 4 | CharacterMovementComponent |
| BrakingDecelerationFalling | 0x208 | 4 | CharacterMovementComponent |
| BrakingDecelerationSwimming | 0x20c | 4 | CharacterMovementComponent |
| BrakingDecelerationFlying | 0x210 | 4 | CharacterMovementComponent |
| AirControl | 0x214 | 4 | CharacterMovementComponent |
| AirControlBoostMultiplier | 0x218 | 4 | CharacterMovementComponent |
| AirControlBoostVelocityThreshold | 0x21c | 4 | CharacterMovementComponent |
| FallingLateralFriction | 0x220 | 4 | CharacterMovementComponent |
| CrouchedHalfHeight | 0x224 | 4 | CharacterMovementComponent |
| Buoyancy | 0x228 | 4 |  |
| PerchRadiusThreshold | 0x22c | 4 | CharacterMovementComponent |
| PerchAdditionalHeight | 0x230 | 4 | CharacterMovementComponent |
| RotationRate | 0x234 | 12 | Rotator |
| bUseSeparateBrakingFriction | 0x240 | 1 |  |
| bApplyGravityWhileJumping | 0x240 | 1 |  |
| bUseControllerDesiredRotation | 0x240 | 1 |  |
| bOrientRotationToMovement | 0x240 | 1 |  |
| bSweepWhileNavWalking | 0x240 | 1 |  |
| bMovementInProgress | 0x240 | 1 |  |
| bEnableScopedMovementUpdates | 0x240 | 1 |  |
| bEnableServerDualMoveScopedMovementUpdates | 0x241 | 1 |  |
| bForceMaxAccel | 0x241 | 1 |  |
| bRunPhysicsWithNoController | 0x241 | 1 |  |
| bForceNextFloorCheck | 0x241 | 1 |  |
| bShrinkProxyCapsule | 0x241 | 1 |  |
| bCanWalkOffLedges | 0x241 | 1 |  |
| bCanWalkOffLedgesWhenCrouching | 0x241 | 1 |  |
| bNetworkSkipProxyPredictionOnNetUpdate | 0x242 | 1 |  |
| bNetworkAlwaysReplicateTransformUpdateTimestamp | 0x242 | 1 |  |
| bDeferUpdateMoveComponent | 0x242 | 1 |  |
| bEnablePhysicsInteraction | 0x242 | 1 |  |
| bTouchForceScaledToMass | 0x242 | 1 |  |
| bPushForceScaledToMass | 0x242 | 1 |  |
| bPushForceUsingZOffset | 0x242 | 1 |  |
| bScalePushForceToVelocity | 0x243 | 1 |  |
| DeferredUpdatedMoveComponent | 0x248 | 8 | SceneComponent |
| MaxOutOfWaterStepHeight | 0x250 | 4 | CharacterMovementComponent |
| OutofWaterZ | 0x254 | 4 | CharacterMovementComponent |
| Mass | 0x258 | 4 | CharacterMovementComponent |
| StandingDownwardForceScale | 0x25c | 4 | CharacterMovementComponent |
| InitialPushForceFactor | 0x260 | 4 | CharacterMovementComponent |
| PushForceFactor | 0x264 | 4 | CharacterMovementComponent |
| PushForcePointZOffsetFactor | 0x268 | 4 | CharacterMovementComponent |
| TouchForceFactor | 0x26c | 4 | CharacterMovementComponent |
| MinTouchForce | 0x270 | 4 | CharacterMovementComponent |
| MaxTouchForce | 0x274 | 4 | CharacterMovementComponent |
| RepulsionForce | 0x278 | 4 | CharacterMovementComponent |
| Acceleration | 0x27c | 12 | Vector |
| LastUpdateRotation | 0x290 | 16 | Quat |
| LastUpdateLocation | 0x2a0 | 16 | EncVector |
| LastUpdateVelocity | 0x2b0 | 12 | Vector |
| ServerLastTransformUpdateTimeStamp | 0x2bc | 4 | CharacterMovementComponent |
| ServerLastClientGoodMoveAckTime | 0x2c0 | 4 | CharacterMovementComponent |
| ServerLastClientAdjustmentTime | 0x2c4 | 4 | CharacterMovementComponent |
| PendingImpulseToApply | 0x2c8 | 12 | Vector |
| PendingForceToApply | 0x2d4 | 12 | Vector |
| AnalogInputModifier | 0x2e0 | 4 | CharacterMovementComponent |
| MaxSimulationTimeStep | 0x2f0 | 4 | CharacterMovementComponent |
| MaxSimulationIterations | 0x2f4 | 4 | CharacterMovementComponent |
| MaxJumpApexAttemptsPerSimulation | 0x2f8 | 4 | CharacterMovementComponent |
| MaxDepenetrationWithGeometry | 0x2fc | 4 | CharacterMovementComponent |
| MaxDepenetrationWithGeometryAsProxy | 0x300 | 4 | CharacterMovementComponent |
| MaxDepenetrationWithPawn | 0x304 | 4 | CharacterMovementComponent |
| MaxDepenetrationWithPawnAsProxy | 0x308 | 4 | CharacterMovementComponent |
| NetworkSimulatedSmoothLocationTime | 0x30c | 4 | CharacterMovementComponent |
| NetworkSimulatedSmoothRotationTime | 0x310 | 4 | CharacterMovementComponent |
| ListenServerNetworkSimulatedSmoothLocationTime | 0x314 | 4 | CharacterMovementComponent |
| ListenServerNetworkSimulatedSmoothRotationTime | 0x318 | 4 | CharacterMovementComponent |
| NetProxyShrinkRadius | 0x31c | 4 | CharacterMovementComponent |
| NetProxyShrinkHalfHeight | 0x320 | 4 | CharacterMovementComponent |
| NetworkMaxSmoothUpdateDistance | 0x324 | 4 | CharacterMovementComponent |
| NetworkNoSmoothUpdateDistance | 0x328 | 4 | CharacterMovementComponent |
| NetworkMinTimeBetweenClientAckGoodMoves | 0x32c | 4 |  |
| NetworkMinTimeBetweenClientAdjustments | 0x330 | 4 | CharacterMovementComponent |
| NetworkMinTimeBetweenClientAdjustmentsLargeCorrection | 0x334 | 4 | CharacterMovementComponent |
| NetworkLargeClientCorrectionDistance | 0x338 | 4 | CharacterMovementComponent |
| LedgeCheckThreshold | 0x33c | 4 | CharacterMovementComponent |
| JumpOutOfWaterPitch | 0x340 | 4 | CharacterMovementComponent |
| CurrentFloor | 0x344 | 148 | FindFloorResult |
| DefaultLandMovementMode | 0x3d8 | 1 | EMovementMode |
| DefaultWaterMovementMode | 0x3d9 | 1 | EMovementMode |
| GroundMovementMode | 0x3da | 1 | EMovementMode |
| bMaintainHorizontalGroundVelocity | 0x3db | 1 |  |
| bImpartBaseVelocityX | 0x3db | 1 |  |
| bImpartBaseVelocityY | 0x3db | 1 |  |
| bImpartBaseVelocityZ | 0x3db | 1 |  |
| bImpartBaseAngularVelocity | 0x3db | 1 |  |
| bJustTeleported | 0x3db | 1 |  |
| bNetworkUpdateReceived | 0x3db | 1 |  |
| bNetworkMovementModeChanged | 0x3db | 1 |  |
| bIgnoreClientMovementErrorChecksAndCorrection | 0x3dc | 1 |  |
| bServerAcceptClientAuthoritativePosition | 0x3dc | 1 |  |
| bNotifyApex | 0x3dc | 1 |  |
| bCheatFlying | 0x3dc | 1 |  |
| bWantsToCrouch | 0x3dc | 1 |  |
| bCrouchMaintainsBaseLocation | 0x3dc | 1 |  |
| bIgnoreBaseRotation | 0x3dc | 1 |  |
| bFastAttachedMove | 0x3dc | 1 |  |
| bAlwaysCheckFloor | 0x3dd | 1 |  |
| bUseFlatBaseForFloorChecks | 0x3dd | 1 |  |
| bPerformingJumpOff | 0x3dd | 1 |  |
| bWantsToLeaveNavWalking | 0x3dd | 1 |  |
| bUseRVOAvoidance | 0x3dd | 1 |  |
| bRequestedMoveUseAcceleration | 0x3dd | 1 |  |
| bWasSimulatingRootMotion | 0x3dd | 1 |  |
| bAllowPhysicsRotationDuringAnimRootMotion | 0x3de | 1 |  |
| bHasRequestedVelocity | 0x3de | 1 |  |
| bRequestedMoveWithMaxSpeed | 0x3de | 1 |  |
| bWasAvoidanceUpdated | 0x3de | 1 |  |
| bProjectNavMeshWalking | 0x3de | 1 |  |
| bProjectNavMeshOnBothWorldChannels | 0x3de | 1 |  |
| bNavMeshWalkingAvoidBumpy | 0x3df | 1 |  |
| AvoidanceConsiderationRadius | 0x3f0 | 4 | CharacterMovementComponent |
| RequestedVelocity | 0x3f4 | 12 | Vector |
| AvoidanceUID | 0x400 | 4 | CharacterMovementComponent |
| AvoidanceGroup | 0x404 | 4 | NavAvoidanceMask |
| GroupsToAvoid | 0x408 | 4 | NavAvoidanceMask |
| GroupsToIgnore | 0x40c | 4 | NavAvoidanceMask |
| AvoidanceWeight | 0x410 | 4 | CharacterMovementComponent |
| PendingLaunchVelocity | 0x414 | 12 | Vector |
| NavMeshProjectionInterval | 0x4d0 | 4 | CharacterMovementComponent |
| NavMeshProjectionTimer | 0x4d4 | 4 | CharacterMovementComponent |
| NavMeshEnterInterval | 0x4d8 | 4 | CharacterMovementComponent |
| NavMeshEnterTimer | 0x4dc | 4 | CharacterMovementComponent |
| NavMeshProjectionInterpSpeed | 0x4e0 | 4 | CharacterMovementComponent |
| NavMeshProjectionHeightScaleUp | 0x4e4 | 4 | CharacterMovementComponent |
| NavMeshProjectionHeightScaleDown | 0x4e8 | 4 | CharacterMovementComponent |
| NavWalkingFloorDistTolerance | 0x4ec | 4 | CharacterMovementComponent |
| NavWalkingLerpHeight | 0x4f0 | 4 | CharacterMovementComponent |
| NavWalkingLerpDist | 0x4f4 | 4 | CharacterMovementComponent |
| PostPhysicsTickFunction | 0x508 | 104 | CharacterMovementComponentPostPhysicsTickFunction |
| MinTimeBetweenTimeStampResets | 0x588 | 4 |  |
| CurrentRootMotion | 0x590 | 248 | RootMotionSourceGroup |
| RootMotionParams | 0x720 | 64 | RootMotionMovementParams |
| AnimRootMotionVelocity | 0x760 | 12 | Vector |

## CharacterSpeedFactor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StandPeekSpeedFactor | 0x0 | 4 | CharacterSpeedFactor |
| CrouchPeekSpeedFactor | 0x4 | 4 | CharacterSpeedFactor |
| StandFireSpeedFactor | 0x8 | 4 | CharacterSpeedFactor |
| CrouchFireSpeedFactor | 0xc | 4 | CharacterSpeedFactor |
| ProneFireSpeedFactor | 0x10 | 4 | CharacterSpeedFactor |
| StandAimSpeedFactor | 0x14 | 4 | CharacterSpeedFactor |
| CrouchAimSpeedFactor | 0x18 | 4 | CharacterSpeedFactor |
| ProneAimSpeedFactor | 0x1c | 4 | CharacterSpeedFactor |
| UsingItemSpeedFactor | 0x20 | 4 | CharacterSpeedFactor |
| UsingItemInWaterSpeedFactor | 0x24 | 4 | CharacterSpeedFactor |
| StandHoldBreathSpeedFactor | 0x28 | 4 | CharacterSpeedFactor |
| CrouchHoldBreathSpeedFactor | 0x2c | 4 | CharacterSpeedFactor |
| ProneHoldBreathSpeedFactor | 0x30 | 4 | CharacterSpeedFactor |
| PeekAimSpeedFactor | 0x34 | 4 | CharacterSpeedFactor |
| SwimmingSurfaceAimSpeedFactor | 0x38 | 4 |  |

## ChildActorAttachedActorInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Actor | 0x0 | 8 | Actor |
| SocketName | 0x8 | 8 | FindFloorResult |
| RelativeTransform | 0x10 | 48 | Transform |

## ChildActorComponentInstanceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ChildActorName | 0xa8 | 8 | ChildActorAttachedActorInfo |
| AttachedActors | 0xb0 | 16 |  |

## ClassComponentCache

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Class | 0x0 | 8 | Class |
| ActorComponent | 0x8 | 8 | ActorComponent |

## ClassRedirect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ObjectName | 0x0 | 8 | ClassRedirect |
| OldClassName | 0x8 | 8 | ClassRedirect |
| NewClassName | 0x10 | 8 | ClassRedirect |
| OldSubobjName | 0x18 | 8 | ClassRedirect |
| NewSubobjName | 0x20 | 8 | ClassRedirect |
| NewClassClass | 0x28 | 8 | ClassRedirect |
| NewClassPackage | 0x30 | 8 | StructRedirect |
| InstanceOnly | 0x38 | 1 |  |

## ClientPingInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ExactPing | 0x0 | 4 | ClientPingInfo |
| DeltaTS | 0x4 | 4 | ClientPingInfo |
| OldPing | 0x8 | 4 | ClientPingInfo |
| DeltaTC | 0xc | 4 | ClientPingInfo |
| ClientDeltaTime | 0x10 | 4 | ClientReturnPingParams |

## ClientReceiveData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LocalPC | 0x0 | 8 | PlayerController |
| MessageType | 0x8 | 8 | ClientReceiveData |
| MessageIndex | 0x10 | 4 | ClientReceiveData |
| MessageString | 0x18 | 16 | BatchedLine |
| RelatedPlayerState | 0x28 | 8 | PlayerState |
| RelatedPlayerState | 0x30 | 8 | PlayerState |
| OptionalObject | 0x38 | 8 | Object |

## ClientReturnPingParams

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ServerReturnedClientTimeStamp | 0x0 | 8 | ClientReturnPingParams |
| DeltaTS | 0x8 | 8 | ClientReturnPingParams |
| InServerTimeStamp | 0x10 | 4 | GPCharacterCameraData |

## ClothPhysicsProperties_Legacy

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| VerticalResistance | 0x0 | 4 | ClothPhysicsProperties_Legacy |
| HorizontalResistance | 0x4 | 4 | ClothPhysicsProperties_Legacy |
| BendResistance | 0x8 | 4 | ClothPhysicsProperties_Legacy |
| ShearResistance | 0xc | 4 | ClothPhysicsProperties_Legacy |
| Friction | 0x10 | 4 | ClothPhysicsProperties_Legacy |
| damping | 0x14 | 4 | ClothPhysicsProperties_Legacy |
| TetherStiffness | 0x18 | 4 | ClothPhysicsProperties_Legacy |
| TetherLimit | 0x1c | 4 | SoundAttenuationSettings |
| Drag | 0x20 | 4 | ClothPhysicsProperties_Legacy |
| StiffnessFrequency | 0x24 | 4 | ClothPhysicsProperties_Legacy |
| GravityScale | 0x28 | 4 | ClothPhysicsProperties_Legacy |
| MassScale | 0x2c | 4 | ClothPhysicsProperties_Legacy |
| InertiaBlend | 0x30 | 4 | ClothPhysicsProperties_Legacy |
| SelfCollisionThickness | 0x34 | 4 | ClothPhysicsProperties_Legacy |
| SelfCollisionSquashScale | 0x38 | 4 | ClothPhysicsProperties_Legacy |
| SelfCollisionStiffness | 0x3c | 4 | ClothPhysicsProperties_Legacy |
| SolverFrequency | 0x40 | 4 | ClothPhysicsProperties_Legacy |
| FiberCompression | 0x44 | 4 | ClothPhysicsProperties_Legacy |
| FiberExpansion | 0x48 | 4 | ClothPhysicsProperties_Legacy |
| FiberResistance | 0x4c | 4 | SingleAnimationPlayData |

## CollisionResponseTemplate

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | CollisionResponseTemplate |
| CollisionEnabled | 0x8 | 1 | ECollisionEnabled |
| bCanModify | 0xa | 1 |  |
| ObjectTypeName | 0x2c | 8 | CustomChannelSetup |
| CustomResponses | 0x38 | 16 |  |

## Color

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| B | 0x0 | 1 |  |
| G | 0x1 | 1 |  |
| R | 0x2 | 1 |  |
| A | 0x3 | 1 |  |

## ConeConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Swing1LimitDegrees | 0x14 | 4 | ConeConstraint |
| Swing2LimitDegrees | 0x18 | 4 | DropNoteInfo |
| Swing1Motion | 0x1c | 1 | EAngularConstraintMotion |
| Swing2Motion | 0x1d | 1 | EAngularConstraintMotion |

## ConstraintBaseParams

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Stiffness | 0x0 | 4 | ConstraintBaseParams |
| damping | 0x4 | 4 | ConstraintBaseParams |
| Restitution | 0x8 | 4 | ConstraintBaseParams |
| ContactDistance | 0xc | 4 | ConstraintDrive |
| bSoftConstraint | 0x10 | 1 |  |

## ConstraintDrive

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Stiffness | 0x0 | 4 | ConstraintDrive |
| damping | 0x4 | 4 | ConstraintDrive |
| MaxForce | 0x8 | 4 | AutoCompleteNode |
| bEnablePositionDrive | 0xc | 1 |  |
| bEnableVelocityDrive | 0xc | 1 |  |

## ConstraintProfileProperties

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ProjectionLinearTolerance | 0x0 | 4 | ConstraintProfileProperties |
| ProjectionAngularTolerance | 0x4 | 4 | ConstraintProfileProperties |
| LinearBreakThreshold | 0x8 | 4 | ConstraintProfileProperties |
| AngularBreakThreshold | 0xc | 4 | LinearConstraint |
| LinearLimit | 0x10 | 28 | LinearConstraint |
| ConeLimit | 0x2c | 32 | ConeConstraint |
| TwistLimit | 0x4c | 28 | TwistConstraint |
| LinearDrive | 0x68 | 76 | LinearDriveConstraint |
| AngularDrive | 0xb4 | 76 | AngularDriveConstraint |
| bDisableCollision | 0x100 | 1 |  |
| bParentDominates | 0x100 | 1 |  |
| bEnableProjection | 0x100 | 1 |  |
| bAngularBreakable | 0x100 | 1 |  |
| bLinearBreakable | 0x100 | 1 |  |

## Controller

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PlayerState | 0x378 | 8 | PlayerState |
| OnInstigatedAnyDamage | 0x388 | 16 |  |
| StateName | 0x398 | 8 |  |
| Pawn | 0x3a0 | 8 | Pawn |
| CHARACTER | 0x3b0 | 8 | CHARACTER |
| TransformComponent | 0x3b8 | 8 | SceneComponent |
| ControlRotation | 0x3d8 | 12 | Rotator |
| bAttachToPawn | 0x3e4 | 1 |  |

## ConvolutionBloomSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Texture | 0x0 | 8 | Texture2D |
| size | 0x8 | 4 | ConvolutionBloomSettings |
| CenterUV | 0xc | 8 | Vector2D |
| PreFilterMin | 0x14 | 4 | ConvolutionBloomSettings |
| PreFilterMax | 0x18 | 4 | ConvolutionBloomSettings |
| PreFilterMult | 0x1c | 4 | ConvolutionBloomSettings |
| BufferScale | 0x20 | 4 | GaussianBlurEffectSettings |

## CurveEdEntry

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurveObject | 0x0 | 8 | Object |
| CurveColor | 0x8 | 4 | Color |
| CurveName | 0x10 | 16 | CurveEdEntry |
| bHideCurve | 0x20 | 4 | CurveEdEntry |
| bColorCurve | 0x24 | 4 | CurveEdEntry |
| bFloatingPointColorCurve | 0x28 | 4 | CurveEdEntry |
| bClamp | 0x2c | 4 | CurveEdEntry |
| ClampLow | 0x30 | 4 | CurveEdEntry |
| ClampHigh | 0x34 | 4 | ParameterGroupData |

## CurveEdTab

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TabName | 0x0 | 16 | CurveEdEntry |
| Curves | 0x10 | 16 |  |
| ViewStartInput | 0x20 | 4 | CurveEdTab |
| ViewEndInput | 0x24 | 4 | CurveEdTab |
| ViewStartOutput | 0x28 | 4 | CurveEdTab |
| ViewEndOutput | 0x2c | 4 | IntegralKey |

## CurveTableRowHandle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurveTable | 0x0 | 8 | CurveTable |
| RowName | 0x8 | 8 | GameplayAbilitySpecDef |

## CustomChannelSetup

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Channel | 0x0 | 1 | ECollisionChannel |
| DefaultResponse | 0x1 | 1 | ECollisionResponse |
| bTraceType | 0x2 | 1 |  |
| bStaticObject | 0x3 | 1 |  |
| Name | 0x4 | 8 | CustomProfile |

## CustomDefine

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DefineName | 0x0 | 16 | CustomDefine |
| DefineValue | 0x10 | 16 | ParameterChannelNames |

## CustomInput

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InputName | 0x0 | 8 | CustomOutput |
| UseFloatPrecision | 0x8 | 1 |  |
| Input | 0xc | 12 | ExpressionInput |

## CustomOutput

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OutputName | 0x0 | 8 | CustomDefine |
| OutputType | 0x8 | 1 | ECustomMaterialOutputType |

## CustomProfile

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | CustomTraceMaskFilterName |
| CustomResponses | 0x8 | 16 |  |

## CustomTraceMaskFilterName

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | ChildActorComponentInstanceData |
| FilterType | 0x8 | 1 | ETraceMaskFilter |

## DFMAIAnimalCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bUseHPDamageScaleWithAmmoLevel | 0x40b2 | 1 |  |
| HPDamageScaleCurve | 0x40b8 | 8 | CurveFloat |

## DFMAICharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| UseSpecialFireLocationForCheckTarget | 0x38c2 | 1 |  |
| IgnorActorsForSepcialCheck | 0x38c8 | 16 |  |
| OpenDoorAnimRowName | 0x38d8 | 8 |  |
| bOpenDoor | 0x38e0 | 1 |  |
| ClientSoundMap | 0x38e8 | 80 |  |
| OutLineMeshsOverride | 0x3938 | 16 |  |
| bRemoveCorpse | 0x3948 | 1 |  |
| RemoveCorpseTime | 0x394c | 4 | DFMAICharacter |
| bHideCorpseBeforeRemove | 0x3950 | 1 |  |
| bShouldCreateDeadBody | 0x3951 | 1 |  |
| bShouldCreateCarryBody | 0x3952 | 1 |  |
| bShouldEnterDeadBox | 0x3953 | 1 |  |
| CustomAI2DeathBoxTime | 0x3954 | 4 | DFMAICharacter |
| CustomAICarryBoxTranslucentTime | 0x3958 | 4 | DFMAICharacter |
| OverrideAnimID | 0x3960 | 4 | DFMAICharacter |
| AIDSPoseConfig | 0x3964 | 8 | DFMAICharacter |
| bFighting | 0x396c | 1 |  |
| CallAICapsuleRadiusScale | 0x3970 | 4 | AnimRootMotionInfo |
| RootMotionActionRep | 0x3980 | 240 | RootMotionActionInfo |
| bAIWeaponHidden | 0x3a70 | 1 |  |
| RootMotionActionReps | 0x3a80 | 16 |  |
| PlanningTransitionRep | 0x3a90 | 104 | PlanningTransitionInfo |
| PlanningTransitionReps | 0x3af8 | 16 |  |
| DebugTransitionRep | 0x3c78 | 32 | DebugTransitionPathInfo |
| AIMovementComp | 0x3c98 | 8 | DFMAICharacterMovementComponent |
| MotionActionComponent | 0x3ca0 | 8 | MotionActionComponent |
| MotionActionCustomMontagePlayPos | 0x3ca8 | 4 | DFMAICharacter |
| MotionActionCustomMontageStartPos | 0x3cb0 | 48 | Transform |
| AICharacterLODComponent | 0x3ce0 | 8 | CharacterLODComponent |
| AIAnimDataComp | 0x3ce8 | 8 | GPAIDataComponentAnim |
| HelicopterSpawnComponent | 0x3cf0 | 8 | DFMAIHelicopterSpawnComponent |
| AIMachineGunFocusMode | 0x3cf8 | 1 | EAIMachineGunFocusMode |
| SmallAngleTurnInPlaceDelay | 0x3d08 | 4 | MotionActionMsg_NewTickActionFrame |
| TurnInPlaceTriggerThreshold | 0x3d0c | 4 | SpawnBaseAIInfo |
| GMKillMeGameplayEffect | 0x3d10 | 8 | Class |
| GMKillMeAttributeEffect | 0x3d18 | 8 | Class |
| AIInfo | 0x3d28 | 48 | SpawnBaseAIInfo |
| MuzzleFlashScale | 0x3d58 | 12 | Vector |
| bDisableTeammateAndSelfDamage | 0x3d64 | 1 |  |
| bAlwaysNotIgnoreDamageTrace | 0x3d65 | 1 |  |
| bCollectAnalysisData | 0x3d66 | 1 |  |
| DisableTickComponents | 0x3d70 | 80 |  |
| AggregateTickComponents | 0x3dc0 | 80 |  |
| CharacterTags | 0x3e10 | 16 |  |
| bEnableRippleEffect | 0x3e20 | 1 |  |
| RippleEffectID | 0x3e24 | 8 | DFMAICharacter |
| bEnableLaserEffect | 0x3e2c | 1 |  |
| LaserEffectScale | 0x3e30 | 4 | DFMAICharacter |
| InteractiveWaterComponent | 0x3e38 | 8 | DFMInteractiveWaterComponent |
| CheckPlasmolysisTime | 0x3e40 | 4 | DFMAICharacter |
| bFixImpendingLoc | 0x3e44 | 1 |  |
| ImpendingCheckPlasmolysisTime | 0x3e48 | 4 | DFMAICharacter |
| EffectBaseScale | 0x3e4c | 4 | DFMAICharacter |
| EffectMaxPlayDistance | 0x3e50 | 4 | DFMAICharacter |
| InitMeshOffest | 0x3e54 | 12 | Vector |
| InitImpendingMeshOffest | 0x3e60 | 12 | Vector |
| ShootEffectCurveFloat | 0x3e70 | 8 | CurveFloat |
| DisplaySubtitlesFarthest | 0x3ed4 | 4 | DFMAICharacter |
| CrouchEyePosOffset | 0x3ed8 | 4 | DFMAICharacter |
| ProneEyePosOffset | 0x3edc | 12 | Vector |
| bAllowedReplenish | 0x3ee8 | 1 |  |
| OpenPreDeadDrama | 0x3ee9 | 1 |  |
| BeginPreDeadDrama | 0x3eea | 1 |  |
| AIAnimProxyComp | 0x3ef0 | 8 | GPAIAnimProxyComponent |
| AIEnvInteractComp | 0x3ef8 | 8 | DFMAIEnvironmentInteractComponent |
| WeaponReplicateComponent | 0x3f00 | 8 | WeaponReplicateComponent |
| TeamMarkFxComp | 0x3f08 | 8 | FXResourceContainerComponent |
| AirHitDetectorComp | 0x3f18 | 8 | AirHitDetectorComponent |
| LastCheckStuckLoc | 0x3f20 | 12 | Vector |
| KillCamAttachBoneName | 0x3f2c | 8 | DFMAICharacter |
| KillCamCameraOffset | 0x3f34 | 12 | Vector |
| CurrentCharacterDuty | 0x3f58 | 1 | ECharacterDuty |
| bAllowStuckSuicide | 0x3f5a | 1 |  |
| bForceCloseCheckSucide | 0x3f5b | 1 |  |
| StayTimeLimit | 0x3f5c | 4 | DFMAICharacter |
| LastLoc | 0x3f60 | 12 | Vector |
| LastUpdateLocTime | 0x3f6c | 4 | DFMAICharacter |
| LastHasNav | 0x3f70 | 4 | DFMAICharacter |
| DistanceToTraceFloor | 0x3f74 | 4 | DFMAICharacter |
| RelativeLocationOverride | 0x3f78 | 12 | Vector |
| bDetachFromActorWhenDie | 0x3f84 | 1 |  |
| Doors | 0x3f98 | 16 |  |
| SprintForwardOpenDoorExtraDistance | 0x3fa8 | 4 | DFMAICharacter |
| bIsHideRomytheus | 0x3fac | 1 |  |
| bIgnoreMoveCollision | 0x3fad | 1 |  |
| bUseCarryBodyIgnoreColl | 0x3fae | 1 |  |
| bIsDavid | 0x3faf | 1 |  |
| bShouldPlayDavidVO | 0x3fb0 | 1 |  |
| InterlayerBoxID | 0x3fb4 | 4 | DFMAICharacter |
| InterlayerInventoryIdName | 0x3fb8 | 8 | DFMAICharacter |
| bIsHostage | 0x3fc0 | 1 |  |
| bCallBPServerOnImpendingDeath | 0x3fc9 | 1 |  |
| bIsChainHooked | 0x3fca | 1 |  |
| bAllowBeingDragged | 0x3fcb | 1 |  |
| bForbidBeingDraggedInImpendingDeath | 0x3fcc | 1 |  |
| ClassComponentCache | 0x3fe0 | 16 | ClassComponentCache |
| bIsInBoss05Smoke | 0x4064 | 1 |  |
| bHasSurrendered | 0x4065 | 1 |  |
| bForbidSurrender | 0x4066 | 1 |  |
| bIsPerformingShooting | 0x4067 | 1 |  |
| WeaponManagerComponent | 0x4068 | 8 | MultiWeaponManagerComponent |
| InCustomBeExcutedStage | 0x4070 | 4 |  |
| OnDoDyeingBefore | 0x4078 | 16 |  |
| bEnableImpendingDeathState | 0x4088 | 1 |  |
| bCanBeRescued | 0x4089 | 1 |  |
| bCanDetectRescue | 0x408a | 1 |  |
| bCanDragRescue | 0x408b | 1 |  |
| bForbidCanBeCarry | 0x408c | 1 |  |
| bForbidCanBeAssassinate | 0x408d | 1 |  |
| bUseFightPlayerFilterList | 0x408e | 1 |  |
| FightPlayerFilterList | 0x4090 | 16 |  |
| FriendlyAiCharacterTags | 0x40a0 | 16 |  |
| bStateCanBeTalk | 0x40b0 | 1 |  |
| bStateCanBeCarry | 0x40b1 | 1 |  |

## DFMCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| IgnoreLodOptimizeDis | 0x24a0 | 4 | DFMCharacter |
| PCUnderwaterPPBlendWeightSpeed | 0x24b0 | 4 | DFMCharacter |
| UnderWaterFog_PC | 0x24b4 | 8 | ExponentialHeightFogComponent |
| UnderWaterFog_Mobile | 0x24bc | 8 | ExponentialHeightFogComponent |
| UnderWaterPostProcess | 0x24c4 | 8 | PostProcessComponent |
| WaterCausticProcess | 0x24cc | 8 | DecalComponent |
| DeathWaitRescueTime_Custom | 0x24d8 | 4 | DFMCharacter |
| CharacterEquipComponentCache | 0x24e0 | 8 | CharacterEquipComponent |
| DFMHealthDataComponent | 0x24e8 | 8 | DFMHealthDataComponent |
| DFMBlackboard | 0x24f0 | 8 | DFMBlackboardComponent |
| DFMComboard | 0x24f8 | 8 | DFMComBoardComponent |
| SignificanceComponent | 0x2500 | 8 | SignificanceBase |
| DFMOutLineEffectComponent | 0x2508 | 8 | DFMOutLineEffectComponent |
| DFMAbilityPathTracingComponent | 0x2510 | 8 | DFMAbilityPathTracingComponent |
| GPKnockbackMoveComponent | 0x2518 | 8 | GPKnockbackMoveComponent |
| DFMPerkComponent | 0x2520 | 8 | DFMPerkComponent |
| GPPassiveMoveComponent | 0x2528 | 8 | GPPassiveMoveComponent |
| DFMPlayerNavGuideComponent | 0x2530 | 8 | DFMPlayerNavGuideComponent |
| AttributeDetectorFactorMap | 0x2548 | 80 |  |
| OnTakeWeaponDamageSignature | 0x2598 | 16 |  |
| CharacterHurtFightStateChange | 0x25a8 | 16 |  |
| CharacterFightingStateChange | 0x25b8 | 16 |  |
| bOpenAIActive | 0x25c8 | 1 |  |
| NoPlayerDuration | 0x25cc | 4 | DFMCharacter |
| CheckPlayerRadius | 0x25d0 | 4 | DFMCharacter |
| RayLength | 0x25d4 | 4 | DFMCharacter |
| RayRadius | 0x25d8 | 4 | DFMCharacter |
| WaterRippleEffectActorCreator_Left | 0x25f0 | 8 | Actor |
| WaterRippleEffectActorCreator_Right | 0x25f8 | 8 | Actor |
| WaterRippleEffectActorCreator_RightMove | 0x2600 | 8 | Actor |
| WaterRippleEffectActorCreator_ShortRight | 0x2608 | 8 | Actor |
| WaterRippleEffectActorCreator_ShortRightMove | 0x2610 | 8 | Actor |
| WaterRippleEffectComponent_Left3P | 0x2630 | 8 | SceneComponent |
| WaterRippleEffectComponent_Right3P | 0x2638 | 8 | SceneComponent |
| LastSocketCachedWeapon3P | 0x2650 | 8 | WeaponBase |
| FaceRotationFocusSpeed | 0x2658 | 4 | DFMCharacter |
| SprintComp | 0x2660 | 8 | GPSprintComponent |
| DFMAttributesCenter | 0x2668 | 8 | DFMCharacterAttributeCenterComponent |
| BuffSystemComponent | 0x2670 | 8 | DFMBuffSystemComponent |
| DFMBuffEffectsComp | 0x2678 | 8 | DFMBuffEffectsComponent |
| DFMMovementComp | 0x2680 | 8 | DFMCharacterMovementComponent |
| DFMFSMInstance | 0x2688 | 8 | DFMFSMInstance |
| WeaponTraceSphere | 0x2690 | 8 | SphereComponent |
| bPressWS | 0x2698 | 1 |  |
| bPressWS_W | 0x2699 | 1 |  |
| bPressAD | 0x269a | 1 |  |
| bPressAD_D | 0x269b | 1 |  |
| AccumulatedStruggleTime | 0x269c | 4 |  |
| BuffIdsToRemove | 0x26a0 | 16 |  |
| CharacterFashionComponent | 0x26b0 | 8 | DFMCharacterFashionComponent |
| FashionConfigName | 0x26b8 | 8 | DFMCharacter |
| FashionDefaultConfigName | 0x26c0 | 8 | DFMCharacter |
| DefaultHeroID | 0x26c8 | 8 | DFMCharacter |
| DefaultHeroWatchID | 0x26d0 | 8 | DFMCharacter |
| FashionDefaultWithLocalMesh | 0x26d8 | 1 |  |
| bOwnerIsGod | 0x26e4 | 1 |  |
| bOwnerIsGodDamage | 0x26e5 | 1 |  |
| GodMat | 0x26e8 | 8 | MaterialInterface |
| GodHitFeedBack | 0x26f0 | 8 |  |
| bNonPerceptualMode | 0x26f8 | 1 |  |
| ResCompletenessCacheMap | 0x2700 | 80 |  |
| DPVSReferenceCountMap | 0x2750 | 80 |  |
| AddFractureBuffHeight | 0x27a0 | 4 | DFMCharacter |
| AddDoubleFractureBuffHeight | 0x27a4 | 4 | DFMCharacter |
| LastHurtTime | 0x27a8 | 4 | DFMCharacter |
| BackSafeActor | 0x27b8 | 8 | Actor |
| InSectorAnchor | 0x27c0 | 4 | DFMAICharacter |
| ActionWithCastTimeClass | 0x27f0 | 8 | Class |
| ActionWithCastTimeInstance | 0x27f8 | 8 | DFMActionWithCastTime |
| ActionInterruptedByHealthZero | 0x2800 | 16 |  |
| ActionInterruptedByUserCancel | 0x2810 | 16 |  |
| ActionInterruptedByMovement | 0x2820 | 16 |  |
| ActionInterruptedByWeapon | 0x2830 | 16 |  |
| ActionInterruptedByVehicle | 0x2840 | 16 |  |
| ActionInterruptedByWeaponEvent | 0x2850 | 16 |  |
| OnCharacterAddMeritEvent | 0x2860 | 16 |  |
| OnServerRedeployStart | 0x2870 | 16 |  |
| OnServerRedeployEnd | 0x2880 | 16 |  |
| OnPlayerEscaping | 0x2890 | 16 |  |
| OnClientNotifyAddBuff | 0x28d8 | 16 |  |
| OnClientNotifyRemoveBuff | 0x28e8 | 16 |  |
| OnServerAddBuffBP | 0x28f8 | 16 |  |
| OnServerRemoveBuffBP | 0x2908 | 16 |  |
| OnClientNotifyAddBuffID | 0x2918 | 16 |  |
| OnClientBuffRefresh | 0x2928 | 16 |  |
| OnClientBuffAccurateRefresh | 0x2938 | 16 |  |
| OnClientEffectBuffRefresh | 0x2948 | 16 |  |
| OnClientNotifyAddOverloadBuff | 0x2958 | 16 |  |
| OnClientNotifyRemoveOverloadBuff | 0x2968 | 16 |  |
| LastMakeDamageOrHurtTime | 0x2978 | 4 | DFMCharacter |
| bLastIsHurtFightingState | 0x297c | 1 |  |
| bLastIsFightingState | 0x297d | 1 |  |
| InteractorComponent | 0x2980 | 8 | InteractorComponent |
| HighValueInspectionComponent | 0x2988 | 8 | DFMHighValueInspectionComponent |
| SequenceBinding | 0x2990 | 8 | DFMCharacterSequenceBindingComponent |
| DFMCharacterAppearanceTPP | 0x2998 | 8 | DFMBattleCharacterAppearanceProxyComponent |
| DFMCharacterAppearanceFPP | 0x29a0 | 8 | DFMBattleCharacterAppearanceProxyComponent |
| DFMCharacterBattlefieldEffect | 0x29a8 | 8 | DFMCharacterBattlefieldEffectComponent |
| LeastHurtHeight | 0x29bc | 4 | DFMCharacter |
| LeastFractureHeight | 0x29c0 | 4 | DFMCharacter |
| LeastDieHeight | 0x29c4 | 4 | DFMCharacter |
| TriggerLandedStiffHeight | 0x29c8 | 4 | DFMCharacter |
| CustomTriggerLandedStiffHeight | 0x29cc | 4 | DFMCharacter |
| LandedStiffTime1 | 0x29d0 | 4 | DFMCharacter |
| LandedStiffTime2 | 0x29d4 | 4 | DFMCharacter |
| MaxSpeedScalerAtLandedStiff | 0x29d8 | 4 | DFMCharacter |
| DamageFallHeight | 0x29e0 | 8 | CurveFloat |
| DamageHealthFallHeight | 0x29e8 | 8 | CurveFloat |
| DamageHealthFallHeightCustom | 0x29f0 | 8 | CurveFloat |
| DamageFallHeightCustom | 0x29f8 | 8 | CurveFloat |
| EnableFallingDamage | 0x2a00 | 1 |  |
| MaxRescueAngleLimit | 0x2a04 | 4 | DFMCharacter |
| MaxRescueDistanceLimit | 0x2a08 | 4 | DFMCharacter |
| CachedInteractPointInterval | 0x2a18 | 4 | DFMCharacter |
| bUseHeadLocForFilterCollision | 0x2a40 | 1 |  |
| AroundFortificationArray | 0x2a50 | 16 |  |
| TickRescueCascadeParamInterval | 0x2a64 | 4 |  |
| OwnedRequestedLootingBoxes | 0x2a68 | 16 |  |
| LootingBoxAssistInfos | 0x2a78 | 16 |  |
| RescueTag | 0x2a88 | 8 | GameplayTag |
| DragRescueTag | 0x2a90 | 8 | GameplayTag |
| bEnableDragRescue | 0x2a98 | 1 |  |
| bIsRescueReplacedByDragInSOL | 0x2a99 | 1 |  |
| DefaultInteractTag | 0x2a9c | 8 | GameplayTag |
| GetRedBagTag | 0x2aa4 | 8 | GameplayTag |
| JoinInteractiveEmoteTag | 0x2aac | 8 | GameplayTag |
| TagContainer | 0x2ab8 | 32 | GameplayTagContainer |
| Dis2RescueParamInfo_HD | 0x2ad8 | 80 |  |
| Dis2RescueParamInfo_Mobile | 0x2b28 | 80 |  |
| Dis2DragRescueParamInfo_HD | 0x2b78 | 80 |  |
| Dis2DragRescueParamInfo_Mobile | 0x2bc8 | 80 |  |
| ButterRescueCascadeParamInfo_HD | 0x2c1c | 28 | RescueCascadeParamInfo |
| ButterRescueCascadeParamInfo_Mobile | 0x2c38 | 28 | RescueCascadeParamInfo |
| GetRedBagParamInfo_HD | 0x2c70 | 28 | RescueCascadeParamInfo |
| GetRedBagParamInfo_Mobile | 0x2c8c | 28 | RescueCascadeParamInfo |
| ButterSetRescueFlag | 0x2ca8 | 1 |  |
| CustombActive_HD | 0x2ca9 | 1 |  |
| CustombEnable_HD | 0x2caa | 1 |  |
| CustombNeedHUDFixedPos_HD | 0x2cab | 1 |  |
| CustombIsTagNumOverTwo_HD | 0x2cac | 1 |  |
| CustombIsNeedFilterPre_HD | 0x2cad | 1 |  |
| CustombIsNeedFilter3C_HD | 0x2cae | 1 |  |
| CustombIsNeedShowWhiteDot_HD | 0x2caf | 1 |  |
| CustombUseAimedBoxFilterWhiteDotDir_HD | 0x2cb0 | 1 |  |
| CustomDetectShowWhiteDotHorizontalAngle_HD | 0x2cb4 | 4 | DFMCharacter |
| CustomDetectShowWhiteDotVerticalAngle_HD | 0x2cb8 | 4 | DFMCharacter |
| CustomDetectShowWhiteDotMinRadius_HD | 0x2cbc | 4 | DFMCharacter |
| CustomDetectShowWhiteDotMaxRadius_HD | 0x2cc0 | 4 | DFMCharacter |
| CustombIsNeedShowOutline_HD | 0x2cc4 | 1 |  |
| CustombUseAimedBoxFilterOutlineDir_HD | 0x2cc5 | 1 |  |
| CustomDetectShowOutlineHorizontalAngle_HD | 0x2cc8 | 4 | DFMCharacter |
| CustomDetectShowOutlineVerticalAngle_HD | 0x2ccc | 4 | DFMCharacter |
| CustomDetectShowOutlineMinRadius_HD | 0x2cd0 | 4 | DFMCharacter |
| CustomDetectShowOutlineMaxRadius_HD | 0x2cd4 | 4 | DFMCharacter |
| CustomDetectShowHUDMinRadius_HD | 0x2cd8 | 4 | DFMCharacter |
| CustomDetectShowHUDMaxRadius_HD | 0x2cdc | 4 | DFMCharacter |
| CustomDetectShowHUDBoxCompName_HD | 0x2ce0 | 8 | DFMCharacter |
| CachedCustomDetectShowHUDBoxComp_HD | 0x2ce8 | 8 | BoxComponent |
| CustomDetectShowHUDHorizontalAngle_HD | 0x2cf0 | 4 | DFMCharacter |
| CustomDetectShowHUDVerticalAngle_HD | 0x2cf4 | 4 | DFMCharacter |
| CustombIsNeedInteractPointForward_HD | 0x2cf8 | 1 |  |
| CustombUseAimedBoxFilterHUDDir_HD | 0x2cf9 | 1 |  |
| CustombUseBoxFilterHUDRange_HD | 0x2cfa | 1 |  |
| CustombIsNeedShowToButton_HD | 0x2cfb | 1 |  |
| CustombIsNeedCheckAllowShowWidget_HD | 0x2cfc | 1 |  |
| CustombIsNeedFilterCollision_HD | 0x2cfd | 1 |  |
| CustomHUDType_HD | 0x2cfe | 1 | EInteractorHUDType |
| CustomInteractorPriority_HD | 0x2cff | 1 | EInteractorPriority |
| CustombIsNeedGather_HD | 0x2d00 | 1 |  |
| CustomButtonTitle_HD | 0x2d08 | 24 | DFMCharacter |
| CustombCanJump_HD | 0x2d20 | 1 |  |
| CustombIgnoreCollisionWhenPassShowHUD_HD | 0x2d21 | 1 |  |
| CustombNeedIgnoreSelf_HD | 0x2d22 | 1 |  |
| CustomWhitelist_HD | 0x2d28 | 16 |  |
| CustomCachedCanOverlapInterval_HD | 0x2d38 | 4 | DFMCharacter |
| CustomCachedAllowShowWidgetInterval_HD | 0x2d3c | 4 |  |
| CustomCachedFilterCollisionInterval_HD | 0x2d40 | 4 | DFMCharacter |
| CustomCachedScreenPosInterval_HD | 0x2d44 | 4 | DFMCharacter |
| CustombActive_Mobile | 0x2d48 | 1 |  |
| CustombEnable_Mobile | 0x2d49 | 1 |  |
| CustombIsNeedFilterPre_Mobile | 0x2d4a | 1 |  |
| CustombIsNeedFilter3C_Mobile | 0x2d4b | 1 |  |
| CustombIsNeedShowWhiteDot_Mobile | 0x2d4c | 1 |  |
| CustombUseAimedBoxFilterWhiteDotDir_Mobile | 0x2d4d | 1 |  |
| CustomDetectShowWhiteDotHorizontalAngle_Mobile | 0x2d50 | 4 | DFMCharacter |
| CustomDetectShowWhiteDotVerticalAngle_Mobile | 0x2d54 | 4 | DFMCharacter |
| CustomDetectShowWhiteDotMinRadius_Mobile | 0x2d58 | 4 | DFMCharacter |
| CustomDetectShowWhiteDotMaxRadius_Mobile | 0x2d5c | 4 | DFMCharacter |
| CustombIsNeedShowOutline_Mobile | 0x2d60 | 1 |  |
| CustombUseAimedBoxFilterOutlineDir_Mobile | 0x2d61 | 1 |  |
| CustomDetectShowOutlineHorizontalAngle_Mobile | 0x2d64 | 4 | DFMCharacter |
| CustomDetectShowOutlineVerticalAngle_Mobile | 0x2d68 | 4 | DFMCharacter |
| CustomDetectShowOutlineMinRadius_Mobile | 0x2d6c | 4 | DFMCharacter |
| CustomDetectShowOutlineMaxRadius_Mobile | 0x2d70 | 4 | DFMCharacter |
| CustomDetectShowHUDMinRadius_Mobile | 0x2d74 | 4 | DFMCharacter |
| CustomDetectShowHUDMaxRadius_Mobile | 0x2d78 | 4 | DFMCharacter |
| CustomDetectShowHUDBoxCompName_Mobile | 0x2d7c | 8 | DFMCharacter |
| CachedCustomDetectShowHUDBoxComp_Mobile | 0x2d88 | 8 | BoxComponent |
| CustomDetectShowHUDHorizontalAngle_Mobile | 0x2d90 | 4 | DFMCharacter |
| CustomDetectShowHUDVerticalAngle_Mobile | 0x2d94 | 4 | DFMCharacter |
| CustombIsNeedInteractPointForward_Mobile | 0x2d98 | 1 |  |
| CustombUseAimedBoxFilterHUDDir_Mobile | 0x2d99 | 1 |  |
| CustombUseBoxFilterHUDRange_Mobile | 0x2d9a | 1 |  |
| CustombIsNeedShowToButton_Mobile | 0x2d9b | 1 |  |
| CustombIsNeedCheckAllowShowWidget_Mobile | 0x2d9c | 1 |  |
| CustombIsNeedFilterCollision_Mobile | 0x2d9d | 1 |  |
| CustomHUDType_Mobile | 0x2d9e | 1 | EInteractorHUDType |
| CustomInteractorPriority_Mobile | 0x2d9f | 1 | EInteractorPriority |
| CustombIsNeedGather_Mobile | 0x2da0 | 1 |  |
| CustomButtonSoftIcon_Mobile | 0x2da8 | 40 | Object |
| CustomButtonTitle_Mobile | 0x2dd0 | 24 | DFMCharacter |
| CustombCanJump_Mobile | 0x2de8 | 1 |  |
| CustombIgnoreCollisionWhenPassShowHUD_Mobile | 0x2de9 | 1 |  |
| CustombNeedIgnoreSelf_Mobile | 0x2dea | 1 |  |
| CustomWhitelist_Mobile | 0x2df0 | 16 |  |
| CustomCachedCanOverlapInterval_Mobile | 0x2e00 | 4 | DFMCharacter |
| CustomCachedAllowShowWidgetInterval_Mobile | 0x2e04 | 4 | DFMCharacter |
| CustomCachedFilterCollisionInterval_Mobile | 0x2e08 | 4 | DFMCharacter |
| CustomCachedScreenPosInterval_Mobile | 0x2e0c | 4 | DFMCharacter |
| CustomInteractorType | 0x2e10 | 1 | EInteractorType |
| CustomInteractPointOffset | 0x2e14 | 12 | Vector |
| bForceUseActorLocationForInteractPoint | 0x2e20 | 1 |  |
| CustombUseCheckPreInMaxDis | 0x2e21 | 1 |  |
| CustombUseActorLocForCheckPreInMaxDis | 0x2e22 | 1 |  |
| CustombUseGamepadAsMobile | 0x2e23 | 1 |  |
| InteractPointOffsetInWater | 0x2e24 | 12 | Vector |
| CachedOutlineMeshComponents | 0x2e30 | 16 |  |
| AICharacterForTargetRange | 0x2e40 | 8 | DFMCharacter |
| GMCommandNPCName | 0x2e48 | 8 | DFMCharacter |
| DistanceToAI | 0x2e50 | 4 | DFMCharacter |
| LockOwner | 0x2e58 | 8 | Actor |
| npcName | 0x2e60 | 8 | DFMCharacter |
| PoolName | 0x2e68 | 8 | DFMCharacter |
| PutInOrder | 0x2e70 | 8 | DFMCharacter |
| PoolChosenName | 0x2e78 | 24 | DFMCharacter |
| PoolChosenName_Buffer | 0x2e90 | 16 |  |
| bAssassinatible | 0x2ea0 | 1 |  |
| OverrideTags | 0x2ea8 | 16 |  |
| NightVisionLeftTime | 0x2eb8 | 4 | DFMCharacter |
| NightVisionSwitch | 0x2ebc | 1 |  |
| CharacterName | 0x2ec0 | 8 |  |
| WeaponOverrideAnimIDMap | 0x2ec8 | 80 |  |
| SpawnChecker | 0x2f18 | 8 | AISpawnChecker |
| SpawnPoint | 0x2f20 | 8 | AISpawnPoint |
| NightVisionItemID | 0x2f28 | 8 | DFMCharacter |
| DragonBreathBulletItemID | 0x2f30 | 8 | DFMCharacter |
| DragonBreathBulletHitEffect | 0x2f38 | 8 | DFMCharacter |
| bStopNightVisionSkillTime | 0x2f40 | 1 |  |
| CheckNightVisionTimerHandle | 0x2f48 | 8 | TimerHandle |
| BlendFrameIntervalTimerHandle | 0x2f50 | 8 | TimerHandle |
| CurrentMission | 0x2f58 | 1 |  |
| CurrentGoal | 0x2f59 | 1 |  |
| CurrentMotage | 0x2f60 | 8 | AnimMontage |
| RescuePointR | 0x2f70 | 48 | Transform |
| RescuePointL | 0x2fa0 | 48 | Transform |
| ObserverList | 0x2fd8 | 16 |  |
| LootingState | 0x2fe8 | 1 | EPlayerLootingState |
| bItsPerceptible | 0x2fe9 | 1 |  |
| bSpawnDrugOnDeath | 0x2fea | 1 |  |
| UseSpecialDropCheckData | 0x3060 | 1 |  |
| SpecialDropCheckRadiu | 0x3064 | 4 | DFMCharacter |
| SpecialDropCheckHigh | 0x3068 | 4 | DFMCharacter |
| DroyBodyCheckRadius | 0x306c | 4 | DFMCharacter |
| DropBodylocSucceed | 0x3070 | 12 | Vector |
| DropForwardLen | 0x3080 | 4 | DFMCharacter |
| DropPointReduceLen | 0x3084 | 4 | DFMCharacter |
| CheckDroyBodyBoxHeight | 0x3088 | 4 | DFMCharacter |
| CheckDroyBodyBoxForwardHeight | 0x308c | 4 | DFMCharacter |
| CheckDroyDownLen | 0x3090 | 4 | DFMCharacter |
| SecondCheckDroyBodyBoxHeight | 0x3094 | 4 | DFMCharacter |
| SecondForwardCheckLen | 0x3098 | 4 | DFMCharacter |
| SecondCheckCapsuleRadiu | 0x309c | 4 | DFMCharacter |
| SecondCheckCapsuleHigh | 0x30a0 | 4 | DFMCharacter |
| SecondCheckOffset | 0x30a4 | 12 | Vector |
| DropCheckClassActor | 0x30b0 | 16 |  |
| DropCheckClassActorRange | 0x30c0 | 4 |  |
| bHasSpwanDeadbodyAmmoBox | 0x30c4 | 1 |  |
| bHasSpwanRedEnvelope | 0x30c5 | 1 |  |
| DeadBodyAmmoBoxClass | 0x30c8 | 8 | Class |
| OnRepCharacterPOI | 0x3100 | 16 |  |
| bInMapPOI | 0x3110 | 1 |  |
| bKillMeshWhenDead | 0x3111 | 1 |  |
| DebugLineBatcher | 0x3118 | 8 | ActorComponent |
| OnPickAmmoSucc | 0x3120 | 16 |  |
| OnLocalCharacterPlayUIAudio | 0x3130 | 16 |  |
| OnLocalCharacterStopUIAudio | 0x3140 | 16 |  |
| OnCharacterBeShot | 0x3160 | 16 |  |
| OnCharacterPlayFx | 0x3170 | 16 |  |
| IsUseRebornUI | 0x3180 | 1 |  |
| IsInRedeploy | 0x3181 | 1 |  |
| AllowRedeployHide | 0x3182 | 1 |  |
| CharacterDamagesPartsBoneNameMap | 0x31d8 | 80 |  |
| CharacterPartBoneNameMap | 0x3228 | 80 |  |
| LootingPainRateWhenArmFracture | 0x3278 | 4 | DFMCharacter |
| LootingPainRateWhenDoubleArmFracture | 0x327c | 4 | DFMCharacter |
| SprintTriggerBuffPeriod | 0x3280 | 4 | DFMCharacter |
| LastFireTime | 0x3284 | 4 | DFMCharacter |
| DebugPanel | 0x3288 | 8 | DFMAILabDebugInfo |
| bArrowNeedRebound | 0x3290 | 1 |  |
| bThrowBlockingRotated | 0x3291 | 1 |  |
| bEnableSuperSprint | 0x3292 | 1 |  |
| bCreateHotFixCompoent | 0x32a1 | 1 |  |
| GPHotFixHelperComponent | 0x32a8 | 8 | GPHotFixHelperComponent |
| LastBeHitMakerUin | 0x32b0 | 8 | DFMCharacter |
| bIgnoreDamage | 0x32b8 | 1 |  |
| PlayHitTemp | 0x32cc | 4 | PropertyReplicationHandler |
| OnJailBreakCharacterStateChanged | 0x32d0 | 16 |  |
| TranslucentDynamicMatArr | 0x32e0 | 16 |  |
| MeshComponentArr | 0x32f0 | 16 |  |
| DeadTransparentTween | 0x3300 | 8 | GPTweenFloat |
| Fx1PCamera | 0x3308 | 8 | FXResourceContainerComponent |
| OnPlayerStateRepTrigger | 0x3318 | 16 |  |
| PropertyReplicationHandler | 0x3338 | 16 | PropertyReplicationHandler |
| CachedKillerKillInfo | 0x3348 | 432 | KillInfo |
| CachedKillerModularWeaponInfo | 0x34f8 | 368 | ModularWeaponInfo |
| PendingHitMarkerColor | 0x3674 | 16 | LinearColor |
| FastFireCandidates | 0x36c0 | 80 |  |
| bIsHookBindSpine | 0x3710 | 1 |  |
| MaxFireCrackerDropCount | 0x3714 | 4 | DFMCharacter |
| CurrentFireCrackerDropCount | 0x3718 | 4 | DFMCharacter |
| bRangeEnableAbility | 0x371c | 1 |  |
| ZALCheckChannel | 0x371d | 1 | ECollisionChannel |
| ZALCheckSecondWallLength | 0x3720 | 4 | DFMCharacter |
| ZALCheckWallAngleMin | 0x3724 | 4 | DFMCharacter |
| ZALCheckBoxLength | 0x3728 | 4 | DFMCharacter |
| ZALCheckBoxWide | 0x372c | 4 | DFMCharacter |
| ZALCheckBoxHigh | 0x3730 | 4 | DFMCharacter |
| ZALLeftCheckOffset | 0x3734 | 4 | DFMCharacter |
| ZALLeftCheckForwardOffset | 0x3738 | 4 | DFMCharacter |
| ZALLeftCheckUpOffset | 0x373c | 4 | DFMCharacter |
| ZALRightCheckOffset | 0x3740 | 4 | DFMCharacter |
| ZALRightCheckForwardOffset | 0x3744 | 4 | DFMCharacter |
| ZALRightCheckUpOffset | 0x3748 | 4 | DFMCharacter |
| ZALTraceForwardLength | 0x374c | 4 | DFMCharacter |
| ZALCheckIgnoreCharacter | 0x3750 | 1 |  |
| ZALCheckIgnoreCharacterDistance | 0x3754 | 4 | DFMCharacter |
| CacheCM | 0x3758 | 8 | GPPlayerCameraManager |
| IsInBreakableItemDamageTriggerBox | 0x3788 | 1 |  |
| BreakableItemDamageTriggerBoxScreenEffectName | 0x378c | 8 | DFMCharacter |
| InterDestructibleComponent | 0x37a0 | 8 | CapsuleComponent |
| bEnableCheckPokerBoxFull | 0x381d | 1 |  |
| CharLocDistThreshold | 0x3820 | 4 | DFMCharacter |
| MarkerSocketName | 0x3824 | 8 |  |
| bNearlyUseCapsuleLocation | 0x382c | 1 |  |
| SocketWorldLocationOffset | 0x3830 | 12 | Vector |
| bNeedLerp | 0x383c | 1 |  |
| bCoverTweenEnable | 0x383d | 1 |  |
| CachedMarkerManager | 0x3890 | 8 | GPMarkerManager |
| Boss08Syringe | 0x38a8 | 8 | GPCommercializationItem |
| IgnoreGamePlayModes | 0x38b0 | 16 |  |

## DFMGameState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MatchStartTime | 0x598 | 4 | DFMGameState |
| MaxMatchDuration | 0x5b0 | 4 | DFMGameState |
| ScavConnectJumpTime | 0x5b4 | 4 | DFMGameState |
| MatchInfo | 0x5b8 | 296 | MatchInfo |
| DsBeginMatchReqReceived | 0x6e0 | 1 |  |
| DFMGamePlayerMode | 0x6e1 | 1 | EDFMGamePlayMode |
| DFMGamePlayerSubMode | 0x6e2 | 1 | EDFMGamePlaySubMode |
| DifficultLevel | 0x6e3 | 1 | EGameDifficultLevel |
| bServerStartRecording | 0x6e4 | 1 |  |
| MapConfig | 0x6e8 | 144 | MapConfig |
| FirstLoadTime | 0x824 | 4 | DFMGameState |
| KillStreakTime | 0x828 | 4 | DFMGameState |
| AntiCheatDetectionBroadcastMaxTimes | 0x82c | 4 | DFMGameState |
| InteractExecutorUseScene | 0x830 | 1 | EDataTableUseScene |
| DSRoomId | 0x838 | 8 | DFMGameState |
| SettlementComponent | 0x840 | 8 | DFMSettlementComponent |
| InteractSystemComponent | 0x848 | 8 | InteractSystem |
| SOLInteractSystemBaseComp | 0x850 | 8 | SOLInteractSystemBase |
| MapInfoSystemComponent | 0x858 | 8 | MapInfoSystem |
| WeaponDataAnalysisComponent | 0x860 | 8 | DFMWeaponDataAnalysisComponent |
| MaxTLogPkgPerFrame | 0x868 | 4 | DFMGameState |
| MaxSecTLogPkgPerFrame | 0x86c | 4 | DFMGameState |
| MaxTLogPkgSize | 0x870 | 4 | DFMGameState |
| MinWaittingTLogNumThreshold | 0x874 | 4 | DFMGameState |
| MaxTLogWaitFrameCount | 0x878 | 4 | DFMGameState |
| DefaultTLogWaitSendNum | 0x87c | 4 | DFMGameState |
| DefaultTLogTotalSendNum | 0x880 | 4 | DFMHealthDataComponent |
| DefaultClientTLogWaitSendNum | 0x884 | 4 | DFMGameState |
| DefaultClientTLogTotalSendNum | 0x888 | 4 |  |
| GemSettings | 0x890 | 16 |  |
| SpawnErrorList | 0x8a0 | 16 |  |
| SpawnErrorMap | 0x8b0 | 80 |  |
| bOpenSpawnErrorSync | 0x900 | 1 |  |
| WeaponMysticalSkinPlayerIdMapStruct | 0x908 | 16 |  |
| WeaponMysticalSkinPlayerIdMap | 0x918 | 80 |  |
| bVehicleAutoDestroy | 0x984 | 1 |  |
| VehicleAutoDestroyTime | 0x988 | 4 |  |
| bVehicleCanGetOff | 0x98c | 1 |  |
| bVehicleCanAccommodateOtherMembers | 0x98d | 1 |  |
| bVehicleCanSwap | 0x98e | 1 |  |
| bVehicleGetOffTip | 0x98f | 1 |  |
| bDisableDeploy | 0x990 | 1 |  |
| bDisableDeployHome | 0x991 | 1 |  |
| IgnoreLowHealthEffectModes | 0x998 | 16 |  |
| GSAbilityComponent | 0x9b0 | 8 | GPAbilityGameStateComponent |
| DeformableGameStateComponent | 0x9b8 | 8 | GPDeformableGameStateComponent |
| FreezeZoneManager | 0x9c0 | 8 | GPFreezeZoneManagerComponent |
| AbilityLockerComponent | 0x9c8 | 8 | DFMAbilityLockerComponent |
| BroadcastComponent | 0x9d0 | 8 | DFMBroadcastComponent |
| GameDataCenterComponent | 0x9d8 | 8 | DFMGameDataCenterComponent |
| ScoreStaticsComponent | 0x9e0 | 8 | DFMScoreStatisticsComponent |
| AILabCharacterDebugInfoBunch | 0xb18 | 16 | AILabCharacterDebugInfoBunch |
| AILabIconViewCache | 0xb28 | 80 |  |
| AILabCharacters | 0xb78 | 16 |  |
| bEnableAILabDebug | 0xb88 | 4 | DFMGameState |
| bEnableAIDebug | 0xb8c | 4 |  |
| LocationIconViewCache | 0xb98 | 80 |  |
| AllDebugLocationInfoArray | 0xbe8 | 16 |  |
| DRLGroupIDs | 0xbf8 | 16 |  |
| SmokeVisibleDistanceCurve | 0xc18 | 160 | RuntimeFloatCurve |
| IgnoreMoveCollisionCharacterList | 0xd10 | 16 |  |
| OBStatInfoComponent | 0xd20 | 8 | DFMOBStatInfoComponent |
| bIsHumanMachineMatch | 0xd28 | 1 |  |
| OfflineItemSpaceMap | 0xd30 | 80 |  |
| UseFastRedeploySkillTime | 0xd80 | 16 |  |
| FastRedeployStatus | 0xd90 | 1 |  |
| UseAttackReformSkillTime | 0xd98 | 16 |  |
| UpdateGemLogRate | 0xda8 | 4 |  |
| NetPlayerMicChannels | 0xdb0 | 16 |  |
| NetPlayerSpeakerChannels | 0xdc0 | 16 |  |
| PlayerMicChannels | 0xdd0 | 80 |  |
| PlayerSpeakerChannels | 0xe20 | 80 |  |
| GSBattleFieldMapFutureTags | 0xf18 | 16 |  |
| FinalOffensiveStage | 0xf28 | 4 |  |
| MapPlayerUin2Index | 0xf30 | 80 |  |
| PlayerAnmNameIndexNum | 0xf80 | 4 |  |
| bIsExtremeIsolateMatch | 0xfb0 | 1 |  |

## DFMPlayerCameraManager

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bSeamlessEntryTransition | 0x5560 | 1 |  |
| ProbeChannel | 0x5561 | 1 | ECollisionChannel |
| ProbeSize | 0x5564 | 4 | DFMPlayerCameraManager |
| LogicAudioModeConfig | 0x5568 | 16 |  |
| LogicAudioManager | 0x5578 | 8 | LogicAudioManager |
| EnableLogicAudio | 0x5580 | 1 |  |
| CustomLogicAudioTickInterval | 0x5584 | 4 | DFMPlayerCameraManager |
| DebugAssassinateCamera | 0x5588 | 1 |  |
| DebugBeAssassinateCamera | 0x5589 | 1 |  |
| CheckSelfCapsuleRadius | 0x558c | 4 |  |

## DFMPlayerCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DFMTelescopeComp | 0x38c8 | 8 | DFMTelescopeComponent |
| DFMCharacterBattleClassComp | 0x38d0 | 8 | DFMCharacterBattleClassComponent |
| DFMProcessAIMsgComp | 0x38d8 | 8 | DFMProcessAIMsgComponent |
| GPSpeedScaleDataComp | 0x38e0 | 8 | GPSpeedScaleDataComponent |
| GPActionSequenceComp | 0x38e8 | 8 | GPActionSequenceComponent |
| GPAudioAnimationNotifyPlayerComp | 0x38f0 | 8 | GPAudioAnimationNotifyPlayer |
| GPPhysicalAnimationComp | 0x38f8 | 8 | GPPhysicalAnimationComponent |
| DFMPlayerDataAnalysisComp | 0x3900 | 8 | DFMPlayerDataAnalysisComponent |
| GPStaminaDataComp | 0x3908 | 8 | GPStaminaDataComponent |
| DFMBehaviorFactorComp | 0x3910 | 8 | DFMBehaviorFactorComponent |
| GPVehicleDataComp | 0x3918 | 8 | GPVehicleDataComponent |
| GPAnimDataComp | 0x3920 | 8 | DFMAnimDataComponent |
| DFMCharacterAmbientAudioFSMComp | 0x3928 | 8 | DFMCharacterAmbientAudioFSM |
| GPExplosionEffectComponent | 0x3930 | 8 | GPExplosionEffectComponent |
| GPVoiceComponent | 0x3938 | 8 | GPCharacterVoiceComponent |
| GPAnimProxyComponent | 0x3940 | 8 | GPAnimProxyComponent |
| GPCameraModeComponent | 0x3948 | 8 | GPCameraModeComponent |
| WeaponManagerComponent | 0x3950 | 8 | WeaponManagerComponent |
| WeaponReplicateComponent | 0x3958 | 8 | WeaponReplicateComponent |
| CharacterEquipComponent | 0x3960 | 8 | CharacterEquipComponent |
| InventoryManager | 0x3968 | 8 | InventoryManager |
| InventoryUseItemManager | 0x3970 | 8 | InventoryUseItemManager |
| PlayerCharacterLODComponent | 0x3978 | 8 | CharacterLODComponent |
| DFMFootprintComponent | 0x3980 | 8 | DFMFootprintComponent |
| GPVaultAndClimbComponent | 0x3988 | 8 | GPVaultAndClimbComponent |
| GPSlidingTackleComponent | 0x3990 | 8 | GPSlidingTackleComponent |
| DFMParachuteComponent | 0x3998 | 8 | DFMParachuteComponent |
| DFMHitEffectComponent | 0x39a0 | 8 | DFMHitEffectComponent |
| DFMSkillComponent | 0x39a8 | 8 | DFMSkillComponent |
| GPSkillReplicateComponent | 0x39b0 | 8 | GPSkillReplicateComponent |
| DFMSniperMarkAimedEnemyComponent | 0x39b8 | 8 | DFMSniperMarkAimedEnemyComponent |
| DFMAICharacterScoringComponent | 0x39c0 | 8 | DFMAICharacterScoringComponent |
| SlotChargingComponent | 0x39c8 | 8 | DFMSlotChargingComponent |
| GPRushMoveComponent | 0x39d0 | 8 | GPRushMoveComponent |
| GPRollMoveComponent | 0x39d8 | 8 | GPRollMoveComponent |
| GPRopeComponent | 0x39e0 | 8 | GPRopeComponent |
| DFCommercializationComponent | 0x39e8 | 8 | DFCommercializationComponent |
| GPDiveComponent | 0x39f0 | 8 | GPDiveComponent |
| DFMAudioListenComponent | 0x39f8 | 8 | DFMAudioListenerComponent |
| bPlayerInCombatState | 0x3a10 | 1 |  |
| RescueVoicePath | 0x3a18 | 24 | SoftObjectPath |
| RescueVoice2DPath | 0x3a30 | 24 | SoftObjectPath |
| FlashLightCanvasClass | 0x3a48 | 40 | Class |
| bEnableCharacterPhysicsPush | 0x3a70 | 1 |  |
| RuleInvalidCharacterComponentArray | 0x3a78 | 16 |  |
| bIndependentEmptyInspectAnim | 0x3a88 | 1 |  |
| PreStateRTTCheckMap | 0x3a90 | 80 |  |
| PreStateForRTTTimerHandle | 0x3ae0 | 8 | TimerHandle |
| CurrentPreStateForRTTT | 0x3ae8 | 1 | EFSMCharacterState |
| ScreenParticleEffectComponent | 0x3af0 | 8 | ParticleSystemComponent |
| CharacterPhysicsCapsuleComponent | 0x3af8 | 8 | PhysicsCapsuleComponent |
| CrocodileNum | 0x3b00 | 4 | DFMPlayerCharacter |
| ScrrenAudioID | 0x3b04 | 8 | GPAudioFuturePlayingID |
| DeathCloseEyeEffectName | 0x3b0c | 8 | DFMPlayerNavGuideConfig |
| ScreenEffectIds | 0x3b18 | 80 |  |
| ScreenEffectIdsWithRotation | 0x3b68 | 80 |  |
| CurrentRankSkillID | 0x3bb8 | 4 | DFMPlayerCharacter |
| TeamCampId | 0x3bbc | 4 |  |

## DFMPlayerController

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PlayerStartSpot | 0xb28 | 8 | PlayerStart |
| PlayerSettlementComponent | 0xb30 | 8 | BasePlayerSettlementComponent |
| PlayerDataCenterComponent | 0xb38 | 8 | DFMPlayerDataCenterComponent |
| PlayerReplayComponent | 0xb40 | 8 | ActorComponent |
| PlayerGMComponent | 0xb48 | 8 | PlayerGMComponent |
| GMWeaponComponent | 0xb50 | 8 | GMWeaponComponent |
| DFMPlayerActivityComponent | 0xb58 | 8 | DFMPlayerActivityComponent |
| DFMInGameUpgradeComponent | 0xb60 | 8 | DFMInGameUpgradeComponent |
| HighlightMomentComponent | 0xb68 | 8 | HighlightMomentComponent |
| DFMTGPAInfoComponent | 0xb70 | 8 | DFMTGPAInfoComponent |
| CacheC2SAceEnemyInfoPackages | 0xb80 | 16 |  |
| ServerCacheEnemyInfoPackages | 0xba0 | 16 |  |
| CacheFOV | 0xbb4 | 4 | DFMPlayerController |
| RuleInvalidCharacterComponentArray | 0xc30 | 16 |  |
| ReplayClass | 0xc40 | 8 | Class |
| DFMBattleSpectateModeLogic | 0xc48 | 8 | DFMBattleSpectateModeLogicComponent |
| MotionActionReplicator | 0xc50 | 8 | MotionActionReplicateComponent |
| OnPossessTickNum | 0xc58 | 4 |  |
| SOLPlayerQuestComponent | 0xc60 | 8 | SOLPlayerQuestComponent |
| HudDataReplicator | 0xc68 | 8 | DFMHudDataReplicator |
| AbilityTestActorBPClass | 0xc78 | 8 | Class |
| PickupDeadBodyUinArr | 0xc80 | 16 |  |
| bIsSOL | 0xcf8 | 1 |  |
| WaterStreamer | 0xcfc | 8 | WaterDataAssetsStreamer |
| UnderWaterPostProcess | 0xd0c | 8 | PostProcessComponent |
| bWaitLogin | 0xd15 | 1 |  |
| OBInventoryManager | 0xd88 | 8 | OBInventoryManager |

## DSTickInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| NetServerMaxTickRate | 0x0 | 4 | DSTickInfo |
| FastNetTickSeconds | 0x4 | 4 | GPLocomotionJumpInfo |

## DateTime

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## DeadInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bIsDead | 0x0 | 1 |  |
| DyingTime | 0x4 | 4 | DeadInfo |
| DeadTime | 0x8 | 4 | DeadInfo |
| bMoving | 0xc | 1 |  |
| DeathDirection | 0xd | 1 | EDirection |
| DeathPose | 0xe | 1 | EChracterPoseType |
| DeathDamageType | 0xf | 1 | EDamageType |
| AngleFromShotDir | 0x10 | 4 | DeadInfo |
| RawShotDir | 0x14 | 12 | Vector |
| ShotBone | 0x20 | 8 | DeadInfo |
| RawShotPos | 0x28 | 12 | Vector |
| KillerUin | 0x38 | 8 | DeadInfo |
| KillerGUID | 0x40 | 8 | DeadInfo |
| DeathAnimDelayTime | 0x48 | 4 | DeadInfo |
| SourceWeapon | 0x4c | 8 | WeaponBase |
| DeathLoc | 0x54 | 12 | Vector |
| ServerDeadTime | 0x60 | 4 | GPCharacterBase |

## DebugTransitionInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MotionType | 0x0 | 4 | DFMAICharacter |
| StartPos | 0x4 | 12 | Vector |
| MiddlePos | 0x10 | 12 | Vector |
| EndPos | 0x1c | 12 | Vector |

## DebugTransitionPathInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Transitions | 0x0 | 16 |  |
| AllPath | 0x10 | 16 |  |

## DescRowBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| RowDescription | 0x8 | 8 | MutexQueueItem |

## DesktopDOFConfigs

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DefaultConfig | 0x0 | 20 | PhysicalCameraConfig |
| ZoomingInConfig | 0x14 | 20 | PhysicalCameraConfig |

## DialogueContext

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Speaker | 0x0 | 8 | DialogueVoice |
| Targets | 0x8 | 16 |  |

## DialogueContextMapping

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Context | 0x0 | 24 | DialogueContext |
| SoundWave | 0x18 | 8 | SoundWave |
| LocalizationKeyFormat | 0x20 | 16 |  |
| Proxy | 0x30 | 8 | DialogueSoundWaveProxy |

## DirectionalShadowUseSkylightAOParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FullShadowThreshold | 0x0 | 4 | DirectionalShadowUseSkylightAOParameters |
| ShadowSharpness | 0x4 | 4 | DirectionalShadowUseSkylightAOParameters |
| FadeAoDistance | 0x8 | 4 | DirectionalShadowUseSkylightAOParameters |
| TransitionDistance | 0xc | 4 | DialogueContextMapping |

## DirectoryPath

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Path | 0x0 | 16 |  |

## DistanceDatum

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FadeInDistanceStart | 0x0 | 4 | DistanceDatum |
| FadeInDistanceEnd | 0x4 | 4 | DistanceDatum |
| FadeOutDistanceStart | 0x8 | 4 | DistanceDatum |
| FadeOutDistanceEnd | 0xc | 4 | DistanceDatum |
| Volume | 0x10 | 4 | AudioEQEffect |

## DistributionLookupTable

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| timescale | 0x0 | 4 | FloatRK4SpringInterpolator |
| TimeBias | 0x4 | 4 | Widget |
| Values | 0x8 | 16 |  |
| Op | 0x18 | 1 |  |
| EntryCount | 0x19 | 1 |  |
| EntryStride | 0x1a | 1 |  |
| SubEntryStride | 0x1b | 1 |  |
| LockFlag | 0x1c | 1 |  |

## DropNoteInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x0 | 12 | Vector |
| Rotation | 0xc | 12 | Rotator |
| Comment | 0x18 | 16 | ScreenMessageString |

## DynamicTextureInstance

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Texture | 0x28 | 8 | Texture2D |
| bAttached | 0x30 | 1 |  |
| OriginalRadius | 0x34 | 4 | LevelSimplificationDetails |

## EdGraphPinType

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PinCategory | 0x0 | 8 | EdGraphPinType |
| PinSubCategory | 0x8 | 8 | EdGraphTerminalType |
| PinSubCategoryObject | 0x10 | 8 | Object |
| PinSubCategoryMemberReference | 0x18 | 32 | SimpleMemberReference |
| PinValueType | 0x38 | 28 | EdGraphTerminalType |
| ContainerType | 0x54 | 1 | EPinContainerType |
| bIsArray | 0x55 | 1 |  |
| bIsReference | 0x55 | 1 |  |
| bIsConst | 0x55 | 1 |  |
| bIsWeakPointer | 0x55 | 1 |  |

## EdGraphSchemaAction

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MenuDescription | 0x8 | 24 | EdGraphSchemaAction |
| TooltipDescription | 0x20 | 24 | EdGraphSchemaAction |
| Category | 0x38 | 24 | EdGraphSchemaAction |
| Keywords | 0x50 | 24 | EdGraphSchemaAction |
| Grouping | 0x68 | 4 | EdGraphSchemaAction |
| SectionID | 0x6c | 4 |  |
| MenuDescriptionArray | 0x70 | 16 |  |
| FullSearchTitlesArray | 0x80 | 16 |  |
| FullSearchKeywordsArray | 0x90 | 16 |  |
| FullSearchCategoryArray | 0xa0 | 16 |  |
| LocalizedMenuDescriptionArray | 0xb0 | 16 |  |
| LocalizedFullSearchTitlesArray | 0xc0 | 16 |  |
| LocalizedFullSearchKeywordsArray | 0xd0 | 16 |  |
| LocalizedFullSearchCategoryArray | 0xe0 | 16 |  |
| SearchText | 0xf0 | 16 | LightMapAtlasPackingSettings |

## EdGraphTerminalType

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TerminalCategory | 0x0 | 8 | EdGraphTerminalType |
| TerminalSubCategory | 0x8 | 8 | MemberReference |
| TerminalSubCategoryObject | 0x10 | 8 | Object |
| bTerminalIsConst | 0x18 | 1 |  |
| bTerminalIsWeakPointer | 0x19 | 1 |  |

## EditedDocumentInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EditedObjectPath | 0x0 | 24 | SoftObjectPath |
| SavedViewOffset | 0x18 | 8 | Vector2D |
| SavedZoomAmount | 0x20 | 4 | BPEditorBookmarkNode |
| EditedObject | 0x28 | 8 | Object |

## EditorElement

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Indices | 0x0 | 4 | EditorElement |
| Weights | 0xc | 4 | GridBlendSample |

## EditorImportExportTestDefinition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ImportFilePath | 0x0 | 16 | FilePath |
| ExportFileExtension | 0x10 | 16 | ImportFactorySettingValues |
| bSkipExport | 0x20 | 1 |  |
| FactorySettings | 0x28 | 16 |  |

## EditorMapPerformanceTestDefinition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PerformanceTestmap | 0x0 | 24 | SoftObjectPath |
| TestTimer | 0x18 | 4 | LaunchOnTestSettings |

## EmitterDynamicParameter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ParamName | 0x0 | 8 | InputActionSpeechMapping |
| bUseEmitterTime | 0x8 | 1 |  |
| bSpawnTimeOnly | 0x8 | 1 |  |
| ValueMethod | 0x9 | 1 | EEmitterDynamicParameterValue |
| bScaleVelocityByParamValue | 0xa | 1 |  |
| ParamValue | 0x10 | 48 | RawDistributionFloat |

## EncBoxSphereBounds

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Origin | 0x0 | 16 | EncVector |
| BoxExtent | 0x10 | 12 | Vector |
| SphereRadius | 0x1c | 4 | BoxSphereBounds |

## EncHandler

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Index | 0x0 | 2 | EncHandler |
| bEncrypted | 0x2 | 1 | Vector |
| bDynamic | 0x3 | 1 |  |
| bShareKey | 0x3 | 1 |  |
| bBitwiseCopyable | 0x3 | 1 |  |

## EncVector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | EncVector |
| Y | 0x4 | 4 | EncVector |
| Z | 0x8 | 4 | EncHandler |
| EncHandler | 0xc | 4 | EncHandler |

## ExplicitDisableBitArray

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## ExponentialHeightFogData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SecondFogDensity | 0x0 | 4 | ExponentialHeightFogData |
| SecondFogHeightFalloff | 0x4 | 4 | ExponentialHeightFogData |
| SecondFogHeightOffset | 0x8 | 4 | ExponentialHeightFogData |
| SecondFogStartDistance | 0xc | 4 | GlobalInteriorFogData |

## ExposureSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FixedEV100 | 0x0 | 4 | ExposureSettings |
| bFixed | 0x4 | 1 |  |
| bUseLuminance | 0x5 | 1 |  |
| Fixedluminance | 0x8 | 4 | NetDriverDefinition |

## ExpressionInput

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OutputIndex | 0x0 | 4 | ExpressionInput |
| ExpressionName | 0x4 | 8 | FormatArgumentData |

## ExternalToolDefinition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ToolName | 0x0 | 16 | ExternalToolDefinition |
| ExecutablePath | 0x10 | 16 | FilePath |
| CommandLineOptions | 0x20 | 16 | ExternalToolDefinition |
| WorkingDirectory | 0x30 | 16 | DirectoryPath |
| ScriptExtension | 0x40 | 16 | EditorImportExportTestDefinition |
| ScriptDirectory | 0x50 | 16 | DirectoryPath |

## ExtraOutputPin

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | CustomInput |
| useTexture | 0x8 | 1 |  |
| Input | 0xc | 12 | ExpressionInput |

## FOscillator

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Amplitude | 0x0 | 4 | FOscillator |
| frequency | 0x4 | 4 | CachedAnimStateData |
| InitialOffset | 0x8 | 1 | EInitialOscillatorOffset |
| Waveform | 0x9 | 1 | EOscillatorWaveform |

## FadeInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FadeUITextKeyName | 0x0 | 8 | FadeInfo |
| ShouldShowFadeUI | 0x8 | 1 |  |
| FadeInAlpha | 0xc | 4 | FadeInfo |
| FadeInTime | 0x10 | 4 | FadeInfo |
| FadeOutTime | 0x14 | 4 | FadeInfo |
| DelayOutTime | 0x18 | 4 | FadeInfo |
| MinFadeTime | 0x1c | 4 | FadeInfo |
| Timeout | 0x20 | 4 | AllPlayerLoadLevelCompletedInfo |

## FadeUITextRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FadeUITextKeyName | 0x10 | 8 | FadeUITextRow |
| Title | 0x18 | 24 | FadeUITextRow |
| SubTitle1 | 0x30 | 24 | FadeUITextRow |
| SubTitle2 | 0x48 | 24 | FadeUITextRow |
| Text | 0x60 | 24 | GameMapIdRow |

## FastArraySerializerItem

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ReplicationID | 0x0 | 4 | FastArraySerializerItem |
| ReplicationKey | 0x4 | 4 | FastArraySerializerItem |
| MostRecentArrayReplicationKey | 0x8 | 4 |  |

## FilePath

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FilePath | 0x0 | 16 | PatchMatchRule |

## FindFloorResult

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bBlockingHit | 0x0 | 1 |  |
| bWalkableFloor | 0x0 | 1 |  |
| bLineTrace | 0x0 | 1 |  |
| FloorDist | 0x4 | 4 | FindFloorResult |
| LineDist | 0x8 | 4 | TextSizingParameters |
| HitResult | 0xc | 136 | HitResult |

## FloatDistribution

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Table | 0x0 | 32 | DistributionLookupTable |

## FloatInterval

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Min | 0x0 | 4 | FloatInterval |
| Max | 0x4 | 4 | Int32RangeBound |

## FloatRK4SpringInterpolator

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StiffnessConstant | 0x0 | 4 | DistributionLookupTable |
| DampeningRatio | 0x4 | 4 |  |

## FloatRangeBound

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Type | 0x0 | 1 | ERangeBoundTypes |
| Value | 0x4 | 4 | PrimaryAssetId |

## FontCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StartU | 0x0 | 4 | FontCharacter |
| StartV | 0x4 | 4 | FontCharacter |
| USize | 0x8 | 4 | FontCharacter |
| VSize | 0xc | 4 | FontCharacter |
| TextureIndex | 0x10 | 1 |  |
| VerticalOffset | 0x14 | 4 | ExponentialHeightFogData |

## FontImportOptionsData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FontName | 0x0 | 16 | FontImportOptionsData |
| height | 0x10 | 4 | FontImportOptionsData |
| bEnableAntialiasing | 0x14 | 1 |  |
| bEnableBold | 0x14 | 1 |  |
| bEnableItalic | 0x14 | 1 |  |
| bEnableUnderline | 0x14 | 1 |  |
| bAlphaOnly | 0x14 | 1 |  |
| CharacterSet | 0x15 | 1 | EFontImportCharacterSet |
| Chars | 0x18 | 16 | FontImportOptionsData |
| UnicodeRange | 0x28 | 16 | FontImportOptionsData |
| CharsFilePath | 0x38 | 16 | FontImportOptionsData |
| CharsFileWildcard | 0x48 | 16 | FontImportOptionsData |
| bCreatePrintableOnly | 0x58 | 1 |  |
| bIncludeASCIIRange | 0x58 | 1 |  |
| ForegroundColor | 0x5c | 16 | LinearColor |
| bEnableDropShadow | 0x6c | 1 |  |
| TexturePageWidth | 0x70 | 4 | FontImportOptionsData |
| TexturePageMaxHeight | 0x74 | 4 | FontImportOptionsData |
| XPadding | 0x78 | 4 | FontImportOptionsData |
| YPadding | 0x7c | 4 | FontImportOptionsData |
| ExtendBoxTop | 0x80 | 4 | FontImportOptionsData |
| ExtendBoxBottom | 0x84 | 4 | FontImportOptionsData |
| ExtendBoxRight | 0x88 | 4 | FontImportOptionsData |
| ExtendBoxLeft | 0x8c | 4 | FontImportOptionsData |
| bEnableLegacyMode | 0x90 | 1 |  |
| Kerning | 0x94 | 4 | FontImportOptionsData |
| bUseDistanceFieldAlpha | 0x98 | 1 |  |
| DistanceFieldScaleFactor | 0x9c | 4 | FontImportOptionsData |
| DistanceFieldScanRadiusScale | 0xa0 | 4 | FontCharacter |

## FontParameterValue

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ParameterInfo | 0x0 | 16 | MaterialParameterInfo |
| FontValue | 0x10 | 8 | Font |
| FontPage | 0x18 | 4 | LandscapeLayerTillingsValue |
| ExpressionGUID | 0x1c | 16 | Guid |

## ForceFeedbackParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Tag | 0x0 | 8 | FontImportOptionsData |
| bLooping | 0x8 | 1 |  |
| bIgnoreTimeDilation | 0x9 | 1 |  |
| bPlayWhilePaused | 0xa | 1 |  |

## FormatArgumentData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ArgumentName | 0x0 | 16 | FormatArgumentData |
| ArgumentValueType | 0x10 | 1 | EFormatArgumentType |
| ArgumentValue | 0x18 | 24 | FormatArgumentData |
| ArgumentValueInt | 0x30 | 4 | FormatArgumentData |
| ArgumentValueFloat | 0x34 | 4 | VectorRK4SpringInterpolator |
| ArgumentValueGender | 0x38 | 1 | ETextGender |

## FrameNumber

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Value | 0x0 | 4 | RandomStream |

## FrameRate

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Numerator | 0x0 | 4 | FrameRate |
| Denominator | 0x4 | 4 | FrameNumber |

## FrameTime

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FrameNumber | 0x0 | 4 | FrameNumber |
| SubFrame | 0x4 | 4 | FrameRate |

## FullyLoadedPackagesInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FullyLoadType | 0x0 | 1 | EFullyLoadPackageType |
| Tag | 0x8 | 16 |  |
| PackagesToLoad | 0x18 | 16 |  |
| LoadedObjects | 0x28 | 16 |  |

## GPAudioFuturePlayingID

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ErrorCode | 0x4 | 4 |  |

## GPAutoAimingSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AutoAimingFollowSpringCoeff | 0x0 | 4 | GPAutoAimingSettings |
| AutoAimingConstantFollowSpeed | 0x4 | 4 | GPAutoAimingSettings |
| AutoAimingConstantFollowSpeed_Verti | 0x8 | 4 | GPAutoAimingSettings |
| AutoAimingConstantFollowSpeed_NearFire | 0xc | 4 | GPAutoAimingSettings |
| AutoAimingMaxAngleSpeed | 0x10 | 4 | GPAutoAimingSettings |
| AutoAimingMaxAngleSpeed_NearFire | 0x14 | 4 | GPAutoAimingSettings |
| bUseConstantSpeed | 0x18 | 1 |  |
| AutoAimingDistance_Min | 0x1c | 4 | GPAutoAimingSettings |
| AutoAimingDistance_Max | 0x20 | 4 | GPAutoAimingSettings |
| AutoAimingStartRange | 0x24 | 4 | GPAutoAimingSettings |
| AutoAimingEndRange | 0x28 | 4 | GPAutoAimingSettings |
| AutoAimingTargetOffset | 0x2c | 4 | GPAutoAimingSettings |
| AutoAimingRangeScaleByDis | 0x30 | 4 | GPAutoAimingSettings |
| AutoAimingHeightRate | 0x34 | 4 | GPAutoAimingSettings |
| AutoAimingHeightRate_NearFire | 0x38 | 4 |  |
| AutoAimingMoveCompensateRatio | 0x3c | 4 | GPAutoAimingSettings |
| AutoAimingMoveCompensateDisThresholdSq | 0x40 | 4 | GPAutoAimingSettings |
| AutoAimingMoveCompensateRatio_NearFire | 0x44 | 4 | GPAutoAimingSettings |
| AutoAimingCompensateMaxAngleSpeed | 0x48 | 4 | GPAutoAimingSettings |
| AutoAimingCompensateMaxAngleSpeed_NearFire | 0x4c | 4 | GPAutoAimingSettings |
| AutoAimingQuitThreshold | 0x50 | 4 | GPAutoAimingSettings |
| AutoAimingCheckInterval | 0x54 | 4 | GPAutoAimingSettings |
| RotateDampingCoeff_X | 0x58 | 4 | GPAutoAimingSettings |
| RotateDampingCoeff_Y | 0x5c | 4 | GPAutoAimingSettings |
| RotateDampingRange | 0x60 | 4 | GPAutoAimingSettings |
| bPauseAimingAfterFire | 0x64 | 1 |  |
| FireAimingCoolDownTime | 0x68 | 4 | POVFloatSetting |

## GPCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CharacterDataConfig | 0x1838 | 8 | GPCharacterDataAsset |
| OnBeginKnockback | 0x1880 | 16 |  |
| OnEndKnockback | 0x1890 | 16 |  |
| OnPlayerAssistKill | 0x18a0 | 16 |  |
| OnPlayerKill | 0x18b0 | 16 |  |
| OnPlayerBeKilled | 0x18c0 | 16 |  |
| OnPlayerBeKnockDown | 0x18d0 | 16 |  |
| OnPlayerKnockDownSomeOne | 0x18e0 | 16 |  |
| OnPlayerMakeDamageToVehicle | 0x18f0 | 16 |  |
| OnServerPlayerMakeDamage | 0x1900 | 16 |  |
| OnClientPlayerMakeDamage | 0x1910 | 16 |  |
| OnPlayerAssist | 0x1920 | 16 |  |
| OnKnockDownPlayerAssist | 0x1930 | 16 |  |
| OnExpertIdChangedDelegate | 0x1940 | 16 |  |
| OnGPClientNotifyBuffEffectRefreshSignature | 0x1950 | 16 |  |
| On3PWeaponChangeClip | 0x1960 | 16 |  |
| NotifyFirefightingPlayAnim | 0x1970 | 16 |  |
| OnSwitchZoomRate | 0x1980 | 16 |  |
| OnFishingWeaponActive | 0x1ad0 | 16 |  |
| bProtectFromDying | 0x1ae1 | 1 |  |
| LastBeHitServerTime | 0x1ae4 | 4 | GPCharacter |
| LastNormalFireTime | 0x1ae8 | 4 | GPCharacter |
| CanGetInBattling | 0x1aec | 1 |  |
| BattlingRange | 0x1af0 | 4 | GPCharacter |
| LastInBattlingTime | 0x1af4 | 4 | GPCharacter |
| FireCounts | 0x1af8 | 4 | PoseTransitionTime |
| bIsWaitingStart | 0x1afc | 1 |  |
| PoseTransitionTimeSettings | 0x1b00 | 24 | PoseTransitionTime |
| IsUI | 0x1b18 | 1 |  |
| LastOwnerUin | 0x1b20 | 8 | GPCharacter |
| DisableDynamicPostProcessEffect | 0x1b28 | 1 |  |
| bIsSafeHouseCharacter | 0x1b29 | 1 |  |
| bIsBeingRescueReplicate | 0x1b2a | 1 |  |
| C304SelfRescueCount | 0x1b2c | 4 | GPCharacter |
| C304SelfRescueSucceedCount | 0x1b30 | 4 | GPCharacter |
| C304KillCount | 0x1b34 | 4 | GPCharacter |
| GPCharacterMovement | 0x1b38 | 8 | GPCharacterMovementComponent |
| MovementVelocityScaler | 0x1b40 | 4 | GPCharacter |
| DFGravityScale | 0x1b44 | 4 | GPCharacter |
| CurrentLogicPose | 0x1b48 | 1 | ECharacterLogicPoseType |
| bOnCharacterMeshLoadCompleteFPP | 0x1b54 | 1 |  |
| bOnCharacterMeshLoadCompleteTPP | 0x1b55 | 1 |  |
| ThreatenEnemies | 0x1b58 | 80 |  |
| CharacterCapsuleTransformFormID | 0x1bb4 | 4 | GPCharacter |
| bPivotCameraMode | 0x1bb8 | 1 |  |
| EnableLocomotionTransitionAnimation | 0x1bc8 | 1 |  |
| FootStepMinInterval | 0x1bf0 | 4 | GPCharacter |
| SprintIntervalAfterFire | 0x1bf8 | 4 | GPCharacter |
| FireIntervalAfterSprint | 0x1c00 | 4 | GPCharacter |
| WeaponIndependentFOV | 0x1c0c | 4 | GPCharacter |
| FOVReferenceAspect | 0x1c10 | 4 | GPCharacter |
| ActualAppliedFov | 0x1c14 | 4 | GPCharacter |
| bForceHideFPPMesh | 0x1c18 | 1 |  |
| bTppMeshRefreshBones | 0x1c19 | 1 |  |
| LastCrouchStartTime | 0x1c1c | 4 | GPCharacter |
| LastProneStartTime | 0x1c20 | 4 | GPCharacter |
| LastCrouchInDifferentLocationTime | 0x1c24 | 4 | GPCharacter |
| LastProneInDifferentLocationTime | 0x1c28 | 4 | GPCharacter |
| LastCrouchLocation | 0x1c2c | 12 | Vector |
| LastProneLocation | 0x1c38 | 12 | Vector |
| OnCharacterReloadAmmo | 0x1c48 | 16 |  |
| VehicleDataComponent | 0x1c58 | 8 | GPVehicleDataComponent |
| VaultAndClimbComponent | 0x1c60 | 8 | GPVaultAndClimbComponent |
| AttachParentSocketName | 0x1c68 | 8 | GPCharacter |
| AttachParentSocketTransform | 0x1c70 | 48 | Transform |
| ThisActorLocalTransform | 0x1ca0 | 48 | Transform |
| ImpendingDeathGodTime | 0x1cd0 | 4 |  |
| ImpendingDeathStartTime | 0x1cd4 | 4 | GPCharacter |
| ContinuousJumpPunishTime | 0x1cd8 | 4 |  |
| JumpZVelocityPunishScale | 0x1ce0 | 16 |  |
| JumpLandedTime | 0x1cf0 | 4 | GPCharacter |
| LandedTime | 0x1cf4 | 4 | GPCharacter |
| ContinuousJumpNumber | 0x1cf8 | 4 | GPCharacter |
| MovementInput | 0x1cfc | 8 | Vector2D |
| WorldVelocity | 0x1d04 | 12 | Vector |
| LastFrameWorldPosition | 0x1d10 | 16 | EncVector |
| LastFrameViewRot | 0x1d20 | 12 | Rotator |
| LastFrameActorRot | 0x1d2c | 12 | Vector |
| CurLightBeamEffectNum | 0x1d38 | 4 | GPCharacter |
| bUseConstMovementSpeed | 0x1d3c | 1 |  |
| MeleeBoneName | 0x1d44 | 8 |  |
| BeMarkingByEnemyArray | 0x1d78 | 80 |  |
| BeMarkingEnemyGetScoreMap | 0x1dc8 | 80 |  |
| bNeedFootstepCompensation | 0x1e18 | 1 |  |
| MeleeTraceRange_Override | 0x1e1c | 4 | GPCharacter |
| AttackerValueId_Override | 0x1e20 | 8 | GPCharacter |
| bStingerMissileCanLock | 0x1e28 | 1 |  |
| bEMPEffect | 0x1e29 | 1 |  |
| EMPEffectCount | 0x1e2c | 4 | GPCharacter |
| CachedFrameCount | 0x1e30 | 8 | GPCharacter |
| bIsWeaponEMPAffected | 0x1e38 | 1 |  |
| SummonerPlayer | 0x1e40 | 8 | GPCharacter |
| SummonerSkillId | 0x1e48 | 4 | GPCharacter |
| SummonerAttackValueId | 0x1e50 | 8 | GPCharacter |
| BreathState | 0x1e58 | 1 | EBreathState |
| BreathInfo | 0x1e60 | 8 | BreathInfo |
| GPCharacterConfigComponent | 0x1e70 | 8 | GPCharacterConfigComponent |
| DFMGameplayConfigClass | 0x1e78 | 8 | Class |
| DFMCharacterConfigClass | 0x1e80 | 8 | Class |
| NotifyTeammatesManager | 0x1ea0 | 8 | GPNotifyTeammatesManager |
| DetectEffectComponent2 | 0x1ea8 | 8 | GPCharacterDetectEffectComponent |
| BubbleComponent2 | 0x1eb0 | 8 | GPCharacterBubbleComponent |
| SharedEffectComponent | 0x1eb8 | 8 | GPAbilitySharedEffectComponent |
| WalkStepMaxSpeed | 0x1ec0 | 4 | GPCharacter |
| RunStepMaxSpeed | 0x1ec4 | 4 | GPCharacter |
| SprintStepMaxSpeed | 0x1ec8 | 4 | GPCharacter |
| BlockTheLight_BeingFlashed | 0x1ecc | 8 | GPCharacter |
| AttackerValueId_FlashHitMark | 0x1ed4 | 4 |  |
| FlashLightCanvas | 0x1ed8 | 8 | FlashLightCanvasActor |
| PVSSelfVisibleDist | 0x1ee0 | 16 |  |
| PVSGoalVisibleDist | 0x1ef0 | 16 |  |
| PVSPairVisibleDist | 0x1f00 | 16 |  |
| CharacterCollisionManager | 0x1fb0 | 56 | GPCollisionManager |
| bIsRaiseWatch | 0x1fe8 | 1 |  |
| MaxHealthCurrent | 0x1fec | 4 | GPCharacter |
| MaxHealthBase | 0x1ff0 | 4 | GPCharacter |
| ReplicatedBrakingAcceleration | 0x2014 | 4 | GPCharacter |
| SkillInspectItemKey | 0x2018 | 8 | GPCharacter |
| InspectSkillID | 0x2020 | 4 | GPCharacter |
| DebugFPPPOV | 0x2024 | 1 |  |
| Enable3PPreAppearance | 0x2030 | 1 |  |
| bIsInspecting | 0x2032 | 1 |  |
| WeaponInspectTimerHandle | 0x2038 | 8 | TimerHandle |
| PreWeaponPosition | 0x2040 | 8 |  |
| ControlledActorInfo | 0x2048 | 32 | CharacterControlledActorInfo |
| bDetectedByThermalImaging | 0x2068 | 1 |  |
| AimCapsuleComponent | 0x2070 | 8 | CapsuleComponent |
| bCustomAimCapsuleParams | 0x2079 | 1 |  |
| CustomAimCapsuleRadius | 0x207c | 4 | GPCharacter |
| CustomAimCapsuleHalfHeight | 0x2080 | 4 | GPCharacter |
| CustomAimCapsuleCrouchedHalfHeight | 0x2084 | 4 | GPCharacter |
| CustomAimCapsuleLieDownHalfHeight | 0x2088 | 4 | GPCharacter |
| CustomAimCapsuleSwimHalfHeight | 0x208c | 4 | GPCharacter |
| bCheckBulletDirectionMismatch | 0x2090 | 1 |  |
| InventoryPickup_DeadBody_IsPassShowHUD | 0x2091 | 1 |  |
| ExtraAttachMeshes | 0x20a0 | 16 |  |
| ExtraAttachWeaponMeshes | 0x20b0 | 16 |  |
| SprintFiringInterval | 0x20c0 | 4 | GPCharacter |
| MaxSpeedForSimulated | 0x20c4 | 4 | GPCharacter |
| FireRevealTime | 0x21bc | 4 | GPCharacter |
| MarkingRevealTime | 0x21c0 | 4 |  |
| bFriendlyHitEffectHidden | 0x21dc | 1 |  |

## GPCharacterBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AllFocusedActor | 0xd30 | 16 |  |
| EmptyCachedFocusedActor | 0xd40 | 16 |  |
| bEnableKillZFunction | 0xd50 | 1 |  |
| bResetLastWalkPosFellOutWorld | 0xd50 | 1 |  |
| CharMarkerData | 0xd58 | 24 | CharMarkerData |
| CharOutLineEffectData | 0xd70 | 40 | CharOutLineEffectData |
| CharOutLineEffectDataRep | 0xd98 | 40 | CharOutLineEffectData |
| CacheLastIsAliveForTakeDamage | 0xdc0 | 4 | DeadInfo |
| DeadInfo | 0xdc8 | 104 | DeadInfo |
| DeadLongTimeTolerance | 0xe30 | 4 | GPCharacterBase |
| bDeadCanOPtimise | 0xe34 | 1 |  |
| LastIsDead | 0xe35 | 1 |  |
| MyGUIDValue | 0xe38 | 4 | GPCharacterBase |
| DeathWatchingBattleDelayTime | 0xe3c | 4 | GPCharacterBase |
| bEnableDeathBeRescue | 0xe40 | 1 |  |
| DeathBeRescueNum | 0xe44 | 4 | GPCharacterBase |
| DeathWaitRescueTimeForConfig | 0xe48 | 4 | GPCharacterBase |
| DeathBeRescueResetHPRate | 0xe4c | 4 | GPCharacterBase |
| RebornTimeStamp | 0xe50 | 4 | GPCharacterBase |
| LastRebornTimeStamp | 0xe54 | 4 | GPCharacterBase |
| BeRescuedTimeStamp | 0xe58 | 4 | GPCharacterBase |
| bPalsy | 0xe5c | 1 |  |
| bUseDetachedRagdollMovement | 0xe5e | 1 |  |
| bIsAILab | 0xe5f | 1 |  |
| bIsPlayerAI | 0xe60 | 1 |  |
| bIsPlayerAI_SOL | 0xe61 | 1 |  |
| bIsOfflinePlayer | 0xe62 | 1 |  |
| bOverrideVisibleDistanceFactorThesholds | 0xe63 | 1 |  |
| CapsuleRadius | 0xe64 | 4 | GPCharacterBase |
| CapsuleHalfHeight | 0xe68 | 4 | GPCharacterBase |
| HiddenInGameBitValue | 0xe70 | 8 | GPCharacterBase |
| OnDied | 0xe80 | 16 |  |
| OnReborn | 0xe90 | 16 |  |
| OnClientReborn | 0xea0 | 16 |  |
| OnClientCharacterReborn | 0xeb0 | 16 |  |
| OnServerCharacterReborn | 0xec0 | 16 |  |
| GPCharacterLiveStateChangeSignature | 0xed0 | 16 |  |
| GPCharacterLiveSpectateTargetChange | 0xee0 | 16 |  |
| OnServerGPCharacterBeingRescue | 0xef0 | 16 |  |
| OnServerGPCharacterC304SelfRescue | 0xf00 | 16 |  |
| OnServerGPCharacterRemoteRescue | 0xf10 | 16 |  |
| OnServerGPCharacterBeingCarry | 0xf20 | 16 |  |
| OnServerGPCharacterPreDropCarryBody | 0xf30 | 16 |  |
| OnGPCharacterIsAssassinate | 0xf40 | 16 |  |
| OnGPCharacterBeingAssassinate | 0xf50 | 16 |  |
| OnGPCharacterEnterZipline | 0xf60 | 16 |  |
| GPCharacterAssassinateKill | 0xf70 | 16 |  |
| OnGPCharacterInterruptInteraction | 0xf80 | 16 |  |
| OnSupineStateChangedFor1PorDS | 0xfa8 | 16 |  |
| OnCharacterOBStateChanged | 0xfd8 | 16 |  |
| OnCharacterVOSubtitleSeqFinished | 0xfe8 | 16 |  |
| OnDeadTickNumUpdate | 0xff8 | 16 |  |
| NetworkIdentity | 0x1010 | 8 | GPNetworkIdentityComponent |
| Comboard | 0x1018 | 8 | GPComBoardComponent |
| Blackboard | 0x1020 | 8 | GPBlackboardComponent |
| AdvancedTickingComponent | 0x1028 | 8 | GPAdvancedTickingComponent |
| FSMComponent | 0x1030 | 8 | GPFSMStateMachineComponent |
| FSMInstance | 0x1038 | 8 | GPFSMInstance |
| CameraRealPoint | 0x1040 | 8 | SceneComponent |
| ASC | 0x1048 | 8 | GPASC |
| AttributesCenter | 0x1050 | 8 | GPAttributeCenterComponent |
| CountingTime | 0x1058 | 4 | GPCharacterBase |
| CountingEndTime | 0x105c | 4 | GPCharacterBase |
| OnClientNotifyCounting | 0x1060 | 16 |  |
| OnClientNotifyCountingEndTimeChanged | 0x1070 | 16 |  |
| OnCharacterExpertIdChanged | 0x1080 | 16 |  |
| ViewPointOffset | 0x1090 | 12 | Vector |
| ViewAngle | 0x109c | 4 | GPCharacterBase |
| CharacterGender | 0x10a0 | 1 | ECharacterGender |
| bCanAddForce | 0x10a1 | 1 |  |
| bDebugMode | 0x10a2 | 1 |  |
| DebugStr | 0x10a8 | 16 | GPCharacterBase |
| HealthComp | 0x10b8 | 8 | GPHealthDataComponent |
| TeamComp | 0x10c0 | 8 | GPTeamComponent |
| RagdollComp | 0x10c8 | 8 | GPRagDollPhysicsComponent |
| CameraModeComp | 0x10d0 | 8 | GPCameraModeComponent |
| WeaponAppearanceProxy | 0x10d8 | 8 | WeaponAppearanceProxy |
| PreViewTimelineComponent | 0x10e0 | 8 | PreViewTimelineComponent |
| MaxDeathLifeSpan | 0x10ec | 4 | GPCharacterBase |
| TimeOfDeath | 0x10f0 | 4 |  |
| SpeedFactor | 0x10f4 | 60 | CharacterSpeedFactor |
| SpeedFactorBase | 0x1130 | 60 | CharacterSpeedFactor |
| FactorGainCoefficient | 0x116c | 60 | CharacterSpeedFactor |
| OccupyingCoverPoint | 0x11f0 | 8 | NZCoverPoint |
| bCanBeMarkedByPlayerSOL | 0x11f8 | 1 |  |
| bDeadBoxCanBeMarkedByPlayer | 0x11f9 | 1 |  |
| bCanBeMarkedByPlayerMP | 0x11fa | 1 |  |
| PlayerMarkingTypeArr | 0x1200 | 16 |  |
| PendingDeathOffset | 0x1210 | 12 | Vector |
| DefaultBoxExtent | 0x121c | 12 | Vector |
| PendingDeathBoxExtent | 0x1228 | 12 | Vector |
| CrouchOffset_Reveal | 0x1234 | 12 | Vector |
| ProneOffset_Reveal | 0x1240 | 12 | Vector |
| DefaultBoxExtent_Reveal | 0x124c | 12 | Vector |
| CrouchBoxExtent_Reveal | 0x1258 | 12 | Vector |
| ProneBoxExtent_Reveal | 0x1264 | 12 | Vector |
| InteractivePutWeaponPtr | 0x1270 | 8 | WeaponBase |
| InteractivePutWeaponReasonSet | 0x1278 | 80 |  |
| bEnableMotionGraph | 0x12ca | 1 |  |
| bEnablePhysicsDeath | 0x12cb | 1 |  |
| PhysicsDeathDelay | 0x12cc | 4 | GPCharacterBase |
| bEnableRotationTick | 0x12d0 | 1 |  |
| bEnableCrouchRotationTick | 0x12d1 | 1 |  |
| bEnableProneRotationTick | 0x12d2 | 1 |  |
| FightStateComp | 0x12d8 | 8 | GPFightStateComponent |
| OnCharacterFSMEventMap | 0x12e0 | 80 |  |
| OnFsmTransitionEvent | 0x1330 | 16 |  |
| OnFSMGlobalEvent | 0x1340 | 16 |  |
| OnCameraModeBeginChanged | 0x1350 | 16 |  |
| OnCameraModeEndChanged | 0x1360 | 16 |  |
| LeftArmAnimRowNameFSM | 0x13fc | 8 | GPCharacterBase |
| TargetRotation | 0x1404 | 12 | Rotator |
| CharacterRotation | 0x1410 | 12 | Rotator |
| LookingRotation | 0x141c | 12 | Rotator |
| TurningInstanceLabel | 0x1448 | 8 |  |
| TurningThreashold | 0x1450 | 4 | GPCharacterBase |
| TurningCrouchThreashold | 0x1454 | 4 | GPCharacterBase |
| TurningProneThreashold | 0x1458 | 4 | GPCharacterBase |
| bEnableMovementOptimize | 0x148c | 1 |  |
| OnAimingTriggered | 0x1500 | 16 |  |
| OnUpdateWeaponList | 0x1540 | 16 |  |
| OnUpdateHasSecondaryWeapon | 0x1550 | 16 |  |
| OnUpdateWeaponIDList | 0x1560 | 16 |  |
| OnUpdateCurrentWeapon | 0x1570 | 16 |  |
| OnUpdateWeaponBarWeapon | 0x1580 | 16 |  |
| OnTakeDamageSimple | 0x15a0 | 16 |  |
| OnWeaponLeftHold | 0x15b0 | 16 |  |
| OnMicStateChangeDelegate | 0x1670 | 16 |  |
| OnNightVisionHelmetFaceMask | 0x16b0 | 16 |  |
| OnFppMeshLoadSuccess | 0x16c0 | 16 |  |
| OnCharacterEquipmentVisibleChanged | 0x16e0 | 16 |  |
| CurrentOverrideMovementInfo | 0x16f0 | 2 | RepOverrideMovementInfo |
| CurrentRotationInputScale | 0x16f4 | 4 | ActorMoveMessage |
| LatestMovePackage | 0x16f8 | 44 | ActorMoveMessage |
| GroupCollisionChannel | 0x1724 | 1 | ECollisionChannel |
| UseLeftArmAnimAssets | 0x1728 | 16 |  |
| FaildFireHitCnt | 0x1738 | 4 | GPCharacterBase |
| StopTickComponentClasses | 0x1740 | 16 |  |
| StopTickComponents | 0x1750 | 16 |  |
| FootstepSoundBodyType | 0x176c | 1 | EGPAudioFootSoundBodyType |
| ActorPoolDefaultlPreloadSize | 0x1770 | 4 | GPCharacterBase |
| ActorPoolMaxPoolSize | 0x1774 | 4 |  |
| ActorPoolNetDriverSupport | 0x1778 | 1 |  |
| bCastThirdPersonShadow | 0x1779 | 1 | PerPlatformBool |
| bCastThirdPersonHiddenShadow | 0x177a | 1 | PerPlatformBool |
| bCastFirstPersonShadow | 0x177b | 1 | PerPlatformBool |
| bCurrentWeaponDirty | 0x1785 | 1 |  |
| CacheCurWeapon | 0x1788 | 8 | WeaponBase |
| bCharacterTPPCastShadowGamePlay | 0x1794 | 1 |  |
| bCharacterFPPCastShadowGamePlay | 0x1795 | 1 |  |
| bTPPCastShadowCharacterAppearance | 0x1796 | 1 |  |
| ActorClassCache | 0x17e0 | 8 | Class |
| RescueInfos | 0x17e8 | 16 |  |

## GPCharacterCameraData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OverShoulderNearDistance | 0x0 | 4 | GPCharacterCameraData |
| OverShoulderOffset | 0x4 | 12 | Vector |
| AimDistance | 0x10 | 4 | GPCharacterCameraData |
| AimOffset | 0x14 | 12 | Vector |
| AimPitch | 0x20 | 4 | GPCharacterCameraData |
| AimFOV | 0x24 | 4 | GPAutoAimingSettings |

## GPCollisionManager

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CapsuleComp | 0x0 | 8 | PrimitiveComponent |
| ProneComp | 0x8 | 8 | PrimitiveComponent |
| ActivateProneCollisionState | 0x10 | 16 |  |
| ActivateCapsuleCollisionState | 0x20 | 16 |  |

## GPEnableParachuteByTask

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bEnableParachuteByTask | 0x0 | 1 |  |
| bDirectOpenParachute | 0x1 | 1 |  |
| ChangedCount | 0x4 | 4 | AbilityItemOutLineData |

## GPGameState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bStartMathWithAllPlayerReady | 0x3e8 | 1 |  |
| DamageMode | 0x3e9 | 1 |  |
| DamageFeature | 0x3ea | 1 |  |
| WeaponAmmoLogic | 0x3eb | 1 | EWeaponAmmoLogicType |
| bEnableDamageValidate | 0x3ec | 1 |  |
| AllWaterVolumes | 0x3f0 | 16 |  |
| GameLastTime | 0x400 | 4 | GPGameState |
| OnPlayerRebornEvent | 0x408 | 16 |  |
| FadeStateInfo | 0x418 | 36 | FadeInfo |
| IsInFade | 0x43c | 1 |  |
| ServerFadeOutEvent | 0x440 | 16 |  |
| HasFinished3CGuide | 0x470 | 1 |  |
| bIsLowPerformanceMode | 0x480 | 1 |  |
| KillInfoArray | 0x488 | 16 |  |
| MaxBufferRange | 0x498 | 4 |  |
| ItemInfoBaseProvider | 0x4a0 | 8 | ItemInfoBaseProvider |
| ReconnectSys | 0x4a8 | 8 | ReconnectionSystemBase |
| AllPlayerLoadLevelCompletedInfoArray | 0x4b0 | 16 |  |
| GPMarkerSystem | 0x4c0 | 8 | GPMarkerEffectComponent |
| GPAudioControllerComponent | 0x4c8 | 8 | GPAudioControllerComponent |
| ProjectileGameComponent | 0x4d0 | 8 | GPProjectileGameComponent |
| AudioListenerManagerComponent | 0x4d8 | 8 | GPAudioListenerManagerComponent |
| DSTickInfo | 0x4e0 | 8 | DSTickInfo |
| bServerEnableKnockDownInfo | 0x4e8 | 1 |  |
| KnockDownInfoArrayBuffer | 0x4f0 | 16 |  |

## GPHandIKInstanceProxy

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bUsePreHandIK | 0x798 | 1 |  |
| WeaponIKType | 0x799 | 1 | EHandIKType |
| LeftHandJointLoc | 0x79c | 12 | Vector |
| LeftHandEffectLoc | 0x7a8 | 12 | Vector |
| RightHandJointLoc | 0x7b4 | 12 | Vector |
| ZoomHandOffsetVector | 0x7c0 | 12 | Vector |
| bIsCameraZooming | 0x7cc | 1 |  |
| bShouldCopyIKGun | 0x7cd | 1 |  |
| ZoomHandOffsetBlendOut | 0x7d0 | 4 | GPHandIKInstanceProxy |
| LeftArmIKAlpha | 0x7d4 | 4 | GPHandIKInstanceProxy |
| RightArmIKAlpha | 0x7d8 | 4 | GPHandIKInstanceProxy |
| bDualWeapon | 0x7dc | 1 |  |
| OwnerPawn | 0x7e0 | 8 | GPCharacterBase |
| CurWeapon | 0x7e8 | 8 | WeaponBase |
| CameraModeComponent | 0x7f0 | 8 | GPCameraModeComponent |
| bWeaponDisableIK | 0x7f8 | 1 |  |
| bEnableHandIK | 0x7f9 | 1 |  |
| bOnVehicle | 0x7fa | 1 |  |
| bDisableHandIK | 0x7fb | 1 |  |
| RecordGripOrder | 0x7fc | 4 | GameRoomTypeRow |
| bRecordUnderFPP | 0x800 | 1 |  |

## GPLocomotionJumpInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FallVelocityThreshold_Low | 0x0 | 4 | GPLocomotionJumpInfo |
| FallVelocityThreshold_High | 0x4 | 4 | MemberHealthInfo |
| FallVelocityThreshold_VeryHigh | 0x8 | 4 | GPLocomotionJumpInfo |
| FallVelocityThreshold_Kill | 0xc | 4 | GPLocomotionJumpInfo |
| FallDamagePercent_High | 0x10 | 4 | GPLocomotionJumpInfo |
| FallDamagePercent_VeryHigh | 0x14 | 4 | GPLocomotionJumpInfo |
| FallVelocityThresholdForAnimation_High | 0x18 | 4 | GPLocomotionJumpInfo |
| JumpNearGroundThreashold | 0x1c | 4 | GPLocomotionJumpInfo |
| HealthMAX | 0x20 | 4 | GPLocomotionJumpInfo |
| OwnerHalfHeight | 0x24 | 4 | GPLocomotionJumpInfo |
| OwnerRadius | 0x28 | 4 | GPLocomotionJumpInfo |
| JumpDetectRadiusAdd | 0x2c | 4 | GPZiplineInfo |

## GPLuaQuestData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| quest_id | 0x0 | 8 | GPLuaQuestData |
| quest_state | 0x8 | 4 | GPLuaQuestData |
| quest_accept_time | 0x10 | 8 | GPLuaQuestObjectiveData |
| quest_objectives | 0x18 | 16 |  |
| marked_objective_id | 0x28 | 16 |  |
| expire_time | 0x38 | 8 | GPLuaQuestData |
| marked | 0x40 | 1 |  |
| map_marker | 0x48 | 16 | GPLuaQuestData |
| expire_left_time | 0x58 | 8 | AbilityKnockbackSettingConfig |

## GPLuaQuestObjectiveData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| quest_objective_id | 0x0 | 8 | GPLuaQuestObjectiveData |
| has_completed | 0x8 | 1 |  |
| Value | 0xc | 4 | GPLuaQuestObjectiveData |
| has_marked | 0x10 | 1 |  |
| spent_seconds | 0x18 | 8 | GPLuaQuestObjectiveData |
| required_count | 0x20 | 8 |  |
| accepted_state | 0x28 | 1 |  |

## GPMGameSceneData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SceneName | 0x0 | 8 | GPMGameSceneData |
| Key | 0x8 | 4 | GPMGameSceneData |
| value1 | 0xc | 4 | GPMGameSceneData |
| value2 | 0x10 | 4 | GPMGameSceneData |
| Value3 | 0x14 | 4 | ServerBouncePingParams |

## GPNetworkPlayerController

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DelayCachedViewTarget | 0x6d0 | 8 | Actor |
| LocalFocusActor | 0x6e8 | 8 | Actor |
| EnableLiveSpectatingFeature | 0x6f0 | 1 |  |
| bIsLiveSpectating | 0x6f3 | 1 |  |
| bIsSpectatingAI | 0x6f4 | 1 |  |
| bBeingSpectatingCount | 0x6f8 | 4 |  |
| bIsLiveSpectatingForReset | 0x6fc | 1 |  |
| bServerAILabInDeathWatchFight | 0x6fd | 1 |  |
| CurrentLocalFocusFromServer | 0x778 | 8 | Actor |
| CurrentLocalFocusPlayerPawn | 0x780 | 8 | GPCharacterBase |
| CurrentSpectatingLocalFocusFromServer | 0x788 | 8 | Actor |
| CurrentViewTargetCache | 0x7a8 | 8 | Actor |
| CurrentReplay | 0x7b8 | 8 | Object |

## GPParachuteRepInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StartTimestamp | 0x0 | 4 | GPEnableParachuteByTask |
| OriginPos | 0x4 | 12 | Vector |
| DestPos | 0x10 | 12 | Vector |

## GPPathFollowCheckObstacleConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bEnableCheckingObstacle | 0x0 | 1 |  |
| PredictedTime | 0x4 | 4 | GPParachuteRepInfo |
| CheckChannel | 0x8 | 1 | ECollisionChannel |
| CheckedBoxSize | 0xc | 12 | Vector |
| CheckBoxOffset | 0x18 | 12 | Vector |
| bDrawingCheckBox | 0x24 | 1 |  |
| DrawingCheckBoxColor | 0x28 | 4 | Color |

## GPPathFollowRuntimeData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurrentPath | 0x0 | 8 | Actor |
| CurrentWayPointData | 0x8 | 40 | GPPathFollowWayPointData |
| CurrentDistance | 0x30 | 4 | GPPathFollowRuntimeData |
| CycleNum | 0x34 | 4 | GPPathFollowRuntimeData |
| CurrentSpeed | 0x38 | 4 | GPPathFollowRuntimeData |
| bIsReverse | 0x3c | 1 |  |
| bIsCurrentSpeedFixed | 0x3d | 1 |  |
| bShouldKeepCustomSpeed | 0x3e | 1 |  |
| bTransToCustomSpeed | 0x3f | 1 |  |
| FadingDistance | 0x40 | 4 | GPPathFollowRuntimeData |
| CustomTargetSpeed | 0x44 | 4 | GPPathFollowSnapshotData |
| CurrentTransform | 0x50 | 48 | Transform |

## GPPathFollowSnapshotData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Status | 0x0 | 1 | EGPPathFollowStatus |
| RuntimeData | 0x10 | 144 | GPPathFollowRuntimeData |
| LastPauseReason | 0xa0 | 8 | GPPathFollowCheckObstacleConfig |

## GPPathFollowWayPointData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurrentWayPointIndex | 0x0 | 4 | GPPostprocessDynamicMaterialInfo |
| bNearTargetWayPoint | 0x4 | 1 |  |
| bBackOff | 0x5 | 1 |  |
| bMuteRayTrace | 0x6 | 1 |  |
| RotateSettings | 0x8 | 32 | GPPathWayPointRotateSettings |

## GPPathWayPointPauseSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bAutoResume | 0x0 | 1 |  |
| PauseDuration | 0x4 | 4 | GPPathFollowWayPointData |

## GPPathWayPointRotateSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bIgnoreSplinePitch | 0x0 | 1 |  |
| bIgnoreSplineYaw | 0x1 | 1 |  |
| bIgnoreSplineRoll | 0x2 | 1 |  |
| bOverrideRotator | 0x3 | 1 |  |
| OverrideRotator | 0x4 | 12 | Rotator |
| ExtralRotator | 0x10 | 12 | Rotator |
| InterpSpeed | 0x1c | 4 | GPPathFollowRuntimeData |

## GPPlayerCameraManager

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ZoomInDofConfig | 0x4320 | 36 | MobileDOFConfigs |
| DesktopDOFConfigs | 0x4344 | 40 | DesktopDOFConfigs |
| DefaultMotionBlur | 0x436c | 4 | GPPlayerCameraManager |
| DefaultPPSettings | 0x4370 | 2480 | PostProcessSettings |
| bForceAddDefaultPP | 0x4d20 | 1 |  |
| LastThirdPersonTarget | 0x4d30 | 8 | Actor |
| CurrentCamBonus | 0x4d38 | 4 | GPPlayerCameraManager |
| FlagCamBonus | 0x4d3c | 4 | GPPlayerCameraManager |
| PowerupBonus | 0x4d40 | 4 | GPPlayerCameraManager |
| HigherScoreBonus | 0x4d44 | 4 | GPPlayerCameraManager |
| CurrentActionBonus | 0x4d48 | 4 | GPPlayerCameraManager |
| FPPCameraLerpToAddTimeConfig | 0x4d4c | 4 | GPPlayerCameraManager |
| SwitchViewTargetCurve | 0x4d58 | 8 | CurveFloat |
| SwitchViewTargetFovCurve | 0x4d60 | 8 | CurveFloat |
| ProneViewPitchMin | 0x4dc0 | 4 | GPPlayerCameraManager |
| ProneViewPitchMax | 0x4dc4 | 4 | GPPlayerCameraManager |
| SupineViewPitchMin | 0x4dc8 | 4 | GPPlayerCameraManager |
| SupineViewPitchMax | 0x4dcc | 4 | GPPlayerCameraManager |
| FishingViewPitchMin | 0x4dd0 | 4 |  |
| FishingViewPitchMax | 0x4dd4 | 4 | GPPlayerCameraManager |
| FreeLookModeCameraViewPitchLimit | 0x4dd8 | 8 | Vector2D |
| FreeLookModeCameraViewYawLimit | 0x4de0 | 8 | Vector2D |
| FPPCameraRootName | 0x4dfc | 8 | GPPlayerCameraManager |
| FPPCameraJointName | 0x4e04 | 8 | GPPlayerCameraManager |
| FPPCameraBoneName | 0x4e0c | 8 | GPPlayerCameraManager |
| DragRescueViewPitchMin | 0x4e14 | 4 | GPPlayerCameraManager |
| DragRescueViewPitchMax | 0x4e18 | 4 | GPPlayerCameraManager |
| CameraSmoothTime_Crouch | 0x4e50 | 4 | GPPlayerCameraManager |
| CameraSmoothTime_Prone | 0x4e54 | 4 | GPPlayerCameraManager |
| CameraSmoothTime_QuickCrouch | 0x4e58 | 4 | GPPlayerCameraManager |
| CameraSmoothTime_Parachute | 0x4e5c | 4 | GPPlayerCameraManager |
| CameraSmoothTime_Climb | 0x4e60 | 4 | GPPlayerCameraManager |
| CameraSmoothSpeed_Crouch | 0x4e64 | 4 | GPPlayerCameraManager |
| CameraSmoothSpeed_Prone | 0x4e68 | 4 | GPPlayerCameraManager |
| CameraSmoothSpeed_Climb | 0x4e6c | 4 | GPPlayerCameraManager |
| TargetSocket | 0x4ea0 | 8 | SkeletalMeshSocket |
| FOVDeltaBySpeedCurve | 0x4eb0 | 8 | CurveFloat |
| AttributeSetSpeed | 0x4ec0 | 8 | GPAttributeSetSpeed |
| GPPlayerController | 0x4ec8 | 8 | GPPlayerController |
| ClientBaseSetting | 0x4ed0 | 8 | ClientBaseSetting |
| ClientCameraSettingHD | 0x4ee0 | 8 | ClientCameraSettingHD |
| AimingTarget | 0x4f18 | 8 | GPCharacterBase |
| FPPCameraFOV | 0x4fd0 | 4 | GPPlayerCameraManager |
| ReferenceFPPCameraFov | 0x4fd4 | 4 | GPPlayerCameraManager |
| ReferenceAspectForFixedVerticalFov | 0x4fd8 | 4 | GPPlayerCameraManager |
| bUsingExplosionRadialParams | 0x5109 | 1 |  |
| ActorsToIgnore | 0x5110 | 16 |  |
| CompsToIgnore | 0x5120 | 16 |  |
| GlobalCameraAnimTransformScale | 0x5130 | 4 | GPPlayerCameraManager |
| GlobalPCAnimCameraRotScale | 0x5134 | 4 | GPPlayerCameraManager |
| GlobalMobileAnimCameraRotScale | 0x5138 | 4 | GPPlayerCameraManager |
| GlobalPCAnimCameraLocScale | 0x513c | 4 | GPPlayerCameraManager |
| GlobalMobileAnimCameraLocScale | 0x5140 | 4 | GPPlayerCameraManager |
| bForceUseDefualtCameraStyle | 0x5144 | 1 |  |
| FovAdjustMode | 0x5160 | 1 | EFovAdjustMode |
| FovAdjustMode_Mobile | 0x5161 | 1 | EFovAdjustMode |
| DesignAspect | 0x5164 | 8 | Vector2D |
| DefaultInteractFOV | 0x51a0 | 4 | GPPlayerCameraManager |
| BasicFovForScale | 0x51a4 | 4 |  |
| ChangeSceneFovData | 0x51a8 | 32 | GPSceneFOVChangeDataInfo |
| CameraModeConfig | 0x5328 | 80 |  |
| CameraXppChangeConfig | 0x5378 | 80 |  |
| CameraModifierMapping | 0x53d0 | 80 |  |

## GPPlayerController

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LastPingUpdateTime | 0x7dc | 4 |  |
| ProjectileReplicateComponent | 0x7e8 | 8 | GPProjectileReplicateComponent |
| ClientDataRecordComponent | 0x7f0 | 8 | ClientDataRecordComponent |
| GPTPRC_General | 0x7f8 | 8 | GPTRPCComponent |
| GPTPRC_Quest | 0x800 | 8 | GPTRPCQuestComponent |
| GPPlayerInput | 0x808 | 8 | GPPlayerInput |
| ClientGameData | 0x810 | 8 | ClientGameSetting |
| GPPlayerState | 0x818 | 8 | GPPlayerState |
| CheckPlayerLoadLevelCompletedMap | 0x820 | 80 |  |
| GPCharacter | 0x870 | 8 | GPCharacter |
| GPCharacterMovementComponent | 0x878 | 8 | GPCharacterMovementComponent |
| ImGuiProxy | 0x880 | 8 | ImGuiNetworkProxyComponent |
| GlobalEventProxy | 0x888 | 8 | GlobalEventNetworkProxyComponent |
| MarkingChargeCooldownComponent | 0x890 | 8 | GPMarkingChargeCooldownComponent |
| SprintFiringInterval | 0x898 | 4 | GPPlayerController |
| DeferredSpawnHUDClass | 0x8a0 | 8 | Class |
| AimedActorCache | 0x8a8 | 8 | Actor |
| RTT | 0x8b4 | 4 | GPPlayerController |
| SRTT | 0x8b8 | 4 | GPPlayerController |
| CurrentTimeGap | 0x8bc | 4 | GPPlayerController |
| BulletSystem | 0x920 | 8 | GPWeaponBulletSystem |
| bIsInObserverMode | 0x940 | 1 |  |
| GPSoundVisualizationComponent | 0x948 | 8 | GPSoundVisualizationComponent |
| ReLoginCount | 0x950 | 4 |  |
| ReplicatedGamePlayMode | 0x954 | 1 | EDFMGamePlayMode |
| MyBaseHUD | 0x958 | 8 | BaseHUD |
| GPInputManager | 0x960 | 8 | GPInputManager |
| GPMarkerController | 0x968 | 8 | GPMarkerControllerComponent |
| PlayerControllerAudioComp | 0x970 | 8 | GPControllerAudioComponent |
| PlayerInputClass | 0x980 | 8 | Class |
| PlayerInputClassHD | 0x988 | 8 | Class |
| InputComponentClass | 0x990 | 8 | Class |
| bServerEnableProcessPlayerInput | 0x998 | 1 |  |
| ClientDisableProcessPlayerInputReasons | 0x9a0 | 16 |  |
| bUseDefaultInputTouch | 0xa28 | 1 |  |
| bDebugTick | 0xa62 | 1 |  |
| bShowRecordPanel | 0xa64 | 1 |  |
| ObserverPawnClass | 0xa80 | 8 | Class |
| GPObserverPawn | 0xa88 | 8 | GPObserverPawn |
| ObserverLastGPCharacter | 0xa90 | 8 | GPCharacter |
| bOBCameraPanelShow | 0xa98 | 1 |  |
| InGameConsoleCrossplayType | 0xaac | 4 |  |

## GPPostprocessDynamicMaterialInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EffectPriority | 0x0 | 4 | RagDollReplicateData |
| EffectIndex | 0x4 | 4 | GPMGameSceneData |
| VeryHighPostMaterial | 0x8 | 8 | MaterialInstanceDynamic |
| VeryHighFullScreenMaterial | 0x10 | 8 | MaterialInstanceDynamic |
| VeryHighQuadMesh | 0x18 | 8 | StaticMesh |
| HighPostMaterial | 0x20 | 8 | MaterialInstanceDynamic |
| HighFullScreenMaterial | 0x28 | 8 | MaterialInstanceDynamic |
| HighQuadMesh | 0x30 | 8 | StaticMesh |
| MediumFullScreenMaterial | 0x38 | 8 | MaterialInstanceDynamic |
| MediumQuadMesh | 0x40 | 8 | StaticMesh |
| LowFullScreenMaterial | 0x48 | 8 | MaterialInstanceDynamic |
| LowQuadMesh | 0x50 | 8 | StaticMesh |
| VeryLowFullScreenMaterial | 0x58 | 8 | MaterialInstanceDynamic |
| VeryLowQuadMesh | 0x60 | 8 | StaticMesh |

## GPSceneFOVChangeDataInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## GPUMeshEmitterInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| RequiredModule | 0x0 | 8 | ParticleModuleRequired |
| SpawnModule | 0x8 | 8 | ParticleModuleSpawn |
| SpawnPerUnitModule | 0x10 | 8 | ParticleModuleSpawnPerUnit |
| WindModule | 0x18 | 8 | ParticleModuleWindBase |
| SpawnModules | 0x20 | 16 |  |
| DragCoefficient | 0x30 | 32 | FloatDistribution |
| PointAttractorStrength | 0x50 | 32 | FloatDistribution |
| Resilience | 0x70 | 32 | FloatDistribution |
| ConstantAcceleration | 0x90 | 12 | Vector |
| PointAttractorPosition | 0x9c | 12 | Vector |
| PointAttractorRadiusSq | 0xa8 | 4 | GPUMeshEmitterInfo |
| OrbitOffsetBase | 0xac | 12 | Vector |
| OrbitOffsetRange | 0xb8 | 12 | Vector |
| InvRotationRateScale | 0xc4 | 4 | GPUMeshEmitterInfo |
| MaxLifeTime | 0xc8 | 4 | GPUMeshEmitterInfo |
| MaxParticleCount | 0xcc | 4 | GPUMeshEmitterInfo |
| ScreenAlignment | 0xd0 | 1 | EParticleScreenAlignment |
| bUseMeshLockedAxis | 0xd4 | 4 | GPUMeshEmitterInfo |
| LockedAxis | 0xd8 | 12 | Vector |
| bEnableCollision | 0xe4 | 1 |  |
| CollisionMode | 0xe5 | 1 | EParticleCollisionMode |
| MinFacingCameraBlendDistance | 0xe8 | 4 | GPUMeshEmitterInfo |
| MaxFacingCameraBlendDistance | 0xec | 4 | GPUMeshResourceData |
| DynamicColor | 0xf0 | 72 | RawDistributionVector |
| DynamicAlpha | 0x138 | 48 | RawDistributionFloat |
| DynamicColorScale | 0x168 | 72 | RawDistributionVector |
| DynamicAlphaScale | 0x1b0 | 48 | RawDistributionFloat |
| MeshRotation | 0x1e0 | 72 | RawDistributionVector |

## GPUMeshLocalVectorFieldInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Field | 0x0 | 8 | VectorField |
| Transform | 0x10 | 48 | Transform |
| MinInitialRotation | 0x40 | 12 | Rotator |
| MaxInitialRotation | 0x4c | 12 | Rotator |
| RotationRate | 0x58 | 12 | Rotator |
| Intensity | 0x64 | 4 | GPUMeshLocalVectorFieldInfo |
| Tightness | 0x68 | 4 | GPUMeshEmitterInfo |
| bIgnoreComponentTransform | 0x6c | 1 |  |
| bTileX | 0x6c | 1 |  |
| bTileY | 0x6c | 1 |  |
| bTileZ | 0x6c | 1 |  |
| bUseFixDT | 0x6c | 1 |  |

## GPUMeshResourceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| QuantizedColorSamples | 0x0 | 16 |  |
| QuantizedMiscSamples | 0x10 | 16 |  |
| QuantizedSimulationAttrSamples | 0x20 | 16 |  |
| ColorScale | 0x30 | 16 | Vector4 |
| ColorBias | 0x40 | 16 | Vector4 |
| MiscScale | 0x50 | 16 | Vector4 |
| MiscBias | 0x60 | 16 | Vector4 |
| SimulationAttrCurveScale | 0x70 | 16 | Vector4 |
| SimulationAttrCurveBias | 0x80 | 16 | Vector4 |
| SubImageSize | 0x90 | 16 | Vector4 |
| SizeBySpeed | 0xa0 | 16 | Vector4 |
| ConstantAcceleration | 0xb0 | 12 | Vector |
| OrbitOffsetBase | 0xbc | 12 | Vector |
| OrbitOffsetRange | 0xc8 | 12 | Vector |
| OrbitFrequencyBase | 0xd4 | 12 | Vector |
| OrbitFrequencyRange | 0xe0 | 12 | Vector |
| OrbitPhaseBase | 0xec | 12 | Vector |
| OrbitPhaseRange | 0xf8 | 12 | Vector |
| DragCoefficientScale | 0x104 | 4 | GPUMeshResourceData |
| DragCoefficientBias | 0x108 | 4 | GPUMeshResourceData |
| ResilienceScale | 0x10c | 4 | GPUMeshResourceData |
| ResilienceBias | 0x110 | 4 | GPUMeshResourceData |
| CollisionRadiusScale | 0x114 | 4 | GPUMeshResourceData |
| CollisionRadiusBias | 0x118 | 4 | GPUMeshResourceData |
| CollisionTimeBias | 0x11c | 4 | GPUMeshResourceData |
| CollisionRandomSpread | 0x120 | 4 | GPUMeshResourceData |
| CollisionRandomDistribution | 0x124 | 4 | GPUMeshResourceData |
| CollisionDelayAmount | 0x128 | 4 | GPUMeshResourceData |
| OneMinusFriction | 0x12c | 4 | GPUMeshResourceData |
| RotationRateScale | 0x130 | 4 | RootMotionSource |
| CameraMotionBlurAmount | 0x134 | 4 | GPUMeshResourceData |
| CollisionTargetRotation | 0x140 | 16 | Vector4 |
| ScreenAlignment | 0x150 | 1 | EParticleScreenAlignment |
| MeshAlignment | 0x151 | 1 | EMeshScreenAlignment |
| bRemoveHMDRoll | 0x152 | 1 |  |
| MinFacingCameraBlendDistance | 0x154 | 4 | GPUMeshResourceData |
| MaxFacingCameraBlendDistance | 0x158 | 4 | GPUSpriteLocalVectorFieldInfo |

## GPUSpriteEmitterInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| RequiredModule | 0x0 | 8 | ParticleModuleRequired |
| SpawnModule | 0x8 | 8 | ParticleModuleSpawn |
| SpawnPerUnitModule | 0x10 | 8 | ParticleModuleSpawnPerUnit |
| WindModule | 0x18 | 8 | ParticleModuleWindBase |
| SpawnModules | 0x20 | 16 |  |
| LocalVectorField | 0x30 | 112 | GPUSpriteLocalVectorFieldInfo |
| VectorFieldScale | 0xa0 | 32 | FloatDistribution |
| DragCoefficient | 0xc0 | 32 | FloatDistribution |
| PointAttractorStrength | 0xe0 | 32 | FloatDistribution |
| Resilience | 0x100 | 32 | FloatDistribution |
| ConstantAcceleration | 0x120 | 12 | Vector |
| PointAttractorPosition | 0x12c | 12 | Vector |
| PointAttractorRadiusSq | 0x138 | 4 | GPUSpriteEmitterInfo |
| OrbitOffsetBase | 0x13c | 12 | Vector |
| OrbitOffsetRange | 0x148 | 12 | Vector |
| InvMaxSize | 0x154 | 8 | Vector2D |
| InvRotationRateScale | 0x15c | 4 | GPUSpriteEmitterInfo |
| MaxLifeTime | 0x160 | 4 | GPUSpriteEmitterInfo |
| MaxParticleCount | 0x164 | 4 | GPUSpriteEmitterInfo |
| ScreenAlignment | 0x168 | 1 | EParticleScreenAlignment |
| LockAxisFlag | 0x169 | 1 | EParticleAxisLock |
| bEnableCollision | 0x16a | 1 |  |
| CollisionMode | 0x16b | 1 | EParticleCollisionMode |
| bRemoveHMDRoll | 0x16c | 1 |  |
| MinFacingCameraBlendDistance | 0x170 | 4 | GPUSpriteEmitterInfo |
| MaxFacingCameraBlendDistance | 0x174 | 4 | GPUSpriteResourceData |
| DynamicColor | 0x178 | 72 | RawDistributionVector |
| DynamicAlpha | 0x1c0 | 48 | RawDistributionFloat |
| DynamicColorScale | 0x1f0 | 72 | RawDistributionVector |
| DynamicAlphaScale | 0x238 | 48 | RawDistributionFloat |

## GPUSpriteLocalVectorFieldInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Field | 0x0 | 8 | VectorField |
| Transform | 0x10 | 48 | Transform |
| MinInitialRotation | 0x40 | 12 | Rotator |
| MaxInitialRotation | 0x4c | 12 | Rotator |
| RotationRate | 0x58 | 12 | Rotator |
| Intensity | 0x64 | 4 | GPUSpriteLocalVectorFieldInfo |
| Tightness | 0x68 | 4 | GPUSpriteEmitterInfo |
| bIgnoreComponentTransform | 0x6c | 1 |  |
| bTileX | 0x6c | 1 |  |
| bTileY | 0x6c | 1 |  |
| bTileZ | 0x6c | 1 |  |
| bUseFixDT | 0x6c | 1 |  |

## GPUSpriteResourceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| QuantizedColorSamples | 0x0 | 16 |  |
| QuantizedMiscSamples | 0x10 | 16 |  |
| QuantizedSimulationAttrSamples | 0x20 | 16 |  |
| ColorScale | 0x30 | 16 | Vector4 |
| ColorBias | 0x40 | 16 | Vector4 |
| MiscScale | 0x50 | 16 | Vector4 |
| MiscBias | 0x60 | 16 | Vector4 |
| SimulationAttrCurveScale | 0x70 | 16 | Vector4 |
| SimulationAttrCurveBias | 0x80 | 16 | Vector4 |
| SubImageSize | 0x90 | 16 | Vector4 |
| SizeBySpeed | 0xa0 | 16 | Vector4 |
| ConstantAcceleration | 0xb0 | 12 | Vector |
| OrbitOffsetBase | 0xbc | 12 | Vector |
| OrbitOffsetRange | 0xc8 | 12 | Vector |
| OrbitFrequencyBase | 0xd4 | 12 | Vector |
| OrbitFrequencyRange | 0xe0 | 12 | Vector |
| OrbitPhaseBase | 0xec | 12 | Vector |
| OrbitPhaseRange | 0xf8 | 12 | Vector |
| GlobalVectorFieldScale | 0x104 | 4 | GPUSpriteResourceData |
| GlobalVectorFieldTightness | 0x108 | 4 | GPUSpriteResourceData |
| PerParticleVectorFieldScale | 0x10c | 4 | GPUSpriteResourceData |
| PerParticleVectorFieldBias | 0x110 | 4 | GPUSpriteResourceData |
| DragCoefficientScale | 0x114 | 4 | GPUSpriteResourceData |
| DragCoefficientBias | 0x118 | 4 | GPUSpriteResourceData |
| ResilienceScale | 0x11c | 4 | GPUSpriteResourceData |
| ResilienceBias | 0x120 | 4 | GPUSpriteResourceData |
| CollisionRadiusScale | 0x124 | 4 | GPUSpriteResourceData |
| CollisionRadiusBias | 0x128 | 4 | GPUSpriteResourceData |
| CollisionTimeBias | 0x12c | 4 | GPUSpriteResourceData |
| CollisionRandomSpread | 0x130 | 4 | GPUSpriteResourceData |
| CollisionRandomDistribution | 0x134 | 4 | GPUSpriteResourceData |
| CollisionDelayAmount | 0x138 | 4 | GPUSpriteResourceData |
| OneMinusFriction | 0x13c | 4 | GPUSpriteResourceData |
| RotationRateScale | 0x140 | 4 | GPUSpriteResourceData |
| CameraMotionBlurAmount | 0x144 | 4 | GPUSpriteResourceData |
| ScreenAlignment | 0x148 | 1 | EParticleScreenAlignment |
| LockAxisFlag | 0x149 | 1 | EParticleAxisLock |
| PivotOffset | 0x14c | 8 | Vector2D |
| bRemoveHMDRoll | 0x154 | 1 |  |
| MinFacingCameraBlendDistance | 0x158 | 4 | GPUSpriteResourceData |
| MaxFacingCameraBlendDistance | 0x15c | 4 | BeamTargetData |

## GPZiplineActorInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurrentZiplineActor | 0x0 | 8 | ZiplineInteractorActor |
| DraftGearLocation | 0x8 | 12 | Vector |
| DraftGearRotation | 0x14 | 12 | Rotator |
| LockGearRotation | 0x20 | 12 | Rotator |
| DraftGearDistance | 0x2c | 4 | GPZiplineActorInfo |
| DraftGearRoll | 0x30 | 4 | GPZiplineActorInfo |
| DraftGearLineLength | 0x34 | 4 | GPZiplineActorInfo |
| CurrentMoveSpeed | 0x38 | 4 | GPZiplineActorInfo |
| CurrentZiplineLocation | 0x3c | 12 | Vector |
| CurrentZiplineRotation | 0x48 | 12 | Rotator |
| ZiplineLengthHasMoved | 0x54 | 4 | GPZiplineActorInfo |
| bLerpVerticalRotationFinished | 0x58 | 1 |  |
| bLerpHorizontalRotationFinished | 0x59 | 1 |  |
| bLerpRotationFinished | 0x5a | 1 |  |
| bLerpLocationFinished | 0x5b | 1 |  |
| bEnterIsGreen | 0x5c | 1 |  |
| bCurrentIsInGreenStartArea | 0x5d | 1 |  |
| bCurrentIsInRedStartArea | 0x5e | 1 |  |
| bCurrentIsInSegmentArea | 0x5f | 1 |  |
| GetOffZiplineReason | 0x60 | 1 | EEndZiplineReason |
| bCollisionCheckEnabled | 0x61 | 1 |  |
| ZiplineTriggerEnterCount | 0x64 | 4 | GPZiplineActorInfo |
| bCollisionDetected | 0x68 | 1 |  |
| CollidedActor | 0x6c | 8 | Actor |
| CollisionDropDirection | 0x74 | 12 | Vector |
| LerpTargetLocation | 0x80 | 12 | Vector |
| LerpTargetRotation | 0x8c | 12 | Rotator |
| GetOffZiplineVelocity | 0x98 | 12 | Vector |
| CurrentDraftGearOffset | 0xa4 | 4 | GPZiplineActorInfo |
| ClientMovedLength | 0xa8 | 4 | GPZiplineActorInfo |
| ServerWaitTime | 0xac | 4 |  |
| ServerLocation | 0xb0 | 12 | Vector |
| ForceSet1PMatchServer | 0xbc | 1 |  |

## GPZiplineInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ServerAllowPercentError | 0x0 | 4 | GPZiplineInfo |
| ZiplineCollisionDropSpeed | 0x4 | 4 | GPZiplineInfo |
| ZiplineEndDropSpeed | 0x8 | 4 | GPZiplineInfo |
| ZiplineCancelDropSpeed | 0xc | 4 | GPZiplineInfo |
| VerticalZiplineInCenterCancelDropSpeed | 0x10 | 4 | GPZiplineInfo |
| HorizontalZiplineInCenterCancelDropSpeed | 0x14 | 4 | GPZiplineInfo |
| ZiplineJumpDropUpVerticalSpeed | 0x18 | 4 | GPZiplineInfo |
| ZiplineMoveMaxSpeed | 0x1c | 4 | GPZiplineInfo |
| ZiplineMoveStartSpeed | 0x20 | 4 | GPZiplineInfo |
| ZiplineMoveSpeedAcc | 0x24 | 4 | GPZiplineInfo |
| LerpLocationSpeed | 0x28 | 4 | GPZiplineInfo |
| LerpRotationSpeed | 0x2c | 4 | GPZiplineInfo |
| SweepDistance | 0x30 | 4 | GPZiplineInfo |
| SweepBeginDelayTime | 0x34 | 4 | GPZiplineInfo |
| StartLoopZiplineVoice | 0x38 | 8 | GPAudioEventAsset |
| EndZiplineVoice | 0x40 | 8 | GPAudioEventAsset |
| StartLoopVerticalZiplineVoice | 0x48 | 8 | GPAudioEventAsset |
| EndVerticalZiplineVoice | 0x50 | 8 | GPAudioEventAsset |
| ZiplineRTPCName | 0x58 | 8 | GPZiplineInfo |
| ZiplineScreenEffectMI | 0x60 | 40 | MaterialInstance |
| AttachSocketName | 0x88 | 8 | GPZiplineInfo |
| CouplerLineSlerp | 0x90 | 4 | GPZiplineInfo |
| ServerClientDistanceTolerance | 0x94 | 4 | GPZiplineInfo |
| ServerClientDistanceToleranceVerticalZipline | 0x98 | 4 | GPZiplineInfo |
| ServerWaitClientTime | 0x9c | 4 | GPZiplineInfo |
| ServerUseClientLocErrorTolerance | 0xa0 | 4 | GPZiplineInfo |
| CooldownAfterArrived | 0xa4 | 4 | GPZiplineSimulatedInfo |

## GPZiplineSimulatedInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurrentZiplineActor | 0x0 | 8 | ZiplineInteractorActor |
| bEnterIsGreen | 0x8 | 1 |  |
| CurrentDraftGearOffset | 0xc | 4 | GPHandIKInstanceProxy |
| DraftGearLocation | 0x10 | 12 | Vector |
| DraftGearRotation | 0x1c | 12 | Rotator |
| DraftGearRoll | 0x28 | 4 | GPZiplineSimulatedInfo |
| DraftGearLineLength | 0x2c | 4 | GPZiplineActorInfo |
| LockGearRotation | 0x30 | 12 | Rotator |

## GameMapIdRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GameMapId | 0x10 | 4 | GameMapIdRow |
| MapTypeDes | 0x18 | 16 | GameMapIdRow |
| MapDes | 0x28 | 16 | FadeInfo |

## GameModeTypeRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ServerGameModeType | 0x10 | 4 | GameModeTypeRow |
| MainGameModeType | 0x14 | 4 | GameModeTypeRow |
| SubGameModeType | 0x18 | 4 | GameModeTypeRow |
| Des | 0x20 | 16 | GameModeTypeRow |
| WeaponParamsPath | 0x30 | 16 | FadeUITextRow |

## GameNameRedirect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OldGameName | 0x0 | 8 | GameNameRedirect |
| NewGameName | 0x8 | 8 | ClassRedirect |

## GameRoomTypeRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GameRoomType | 0x10 | 4 | GameRoomTypeRow |
| Des | 0x18 | 16 | GameTeamMemberCountTypeRow |

## GameState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MatchState | 0x3b0 | 8 | GameState |
| PreviousMatchState | 0x3b8 | 8 | GameState |
| ElapsedTime | 0x3c0 | 4 | GameStateBase |

## GameStateBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GameModeClass | 0x370 | 8 | Class |
| AuthorityGameMode | 0x378 | 8 | GameModeBase |
| SpectatorClass | 0x380 | 8 | Class |
| PlayerArray | 0x388 | 16 |  |
| bReplicatedHasBegunPlay | 0x398 | 1 |  |
| ReplicatedWorldTimeSeconds | 0x39c | 4 | GameStateBase |
| ServerWorldTimeSecondsDelta | 0x3a0 | 4 | GameStateBase |
| ServerWorldTimeSecondsUpdateFrequency | 0x3a4 | 4 |  |

## GameTeamMemberCountTypeRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GameTeamMemberCountType | 0x10 | 4 | GameTeamMemberCountTypeRow |
| Des | 0x18 | 16 | GameModeTypeRow |

## GameplayAbilitySpecDef

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Ability | 0x0 | 8 | Class |
| LevelScalableFloat | 0x8 | 32 | ScalableFloat |
| InputID | 0x28 | 4 | GameplayAbilitySpecHandle |
| RemovalPolicy | 0x2c | 1 | EGameplayEffectGrantedAbilityRemovePolicy |
| SourceObject | 0x30 | 8 | Object |
| AssignedHandle | 0x88 | 4 | GameplayAbilitySpecHandle |

## GameplayAbilitySpecHandle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Handle | 0x0 | 4 | GameplayEffectSpec |

## GameplayEffectAttributeCaptureSpecContainer

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SourceAttributes | 0x0 | 16 |  |
| TargetAttributes | 0x10 | 16 |  |
| bHasNonSnapshottedAttributes | 0x20 | 1 |  |

## GameplayEffectContextHandle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## GameplayEffectSpec

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Def | 0x0 | 8 | GameplayEffect |
| ModifiedAttributes | 0x8 | 16 |  |
| CapturedRelevantAttributes | 0x18 | 40 | GameplayEffectAttributeCaptureSpecContainer |
| duration | 0x50 | 4 | GameplayEffectSpec |
| Period | 0x54 | 4 | GameplayEffectSpec |
| ChanceToApplyToTarget | 0x58 | 4 | GameplayTag |
| CapturedSourceTags | 0x60 | 136 | TagContainerAggregator |
| CapturedTargetTags | 0xe8 | 136 | TagContainerAggregator |
| DynamicGrantedTags | 0x170 | 32 | GameplayTagContainer |
| DynamicAssetTags | 0x190 | 32 | GameplayTagContainer |
| Modifiers | 0x1b0 | 16 |  |
| StackCount | 0x1c0 | 4 | ScalableFloat |
| bCompletedSourceAttributeCapture | 0x1c4 | 1 |  |
| bCompletedTargetAttributeCapture | 0x1c4 | 1 |  |
| bDurationLocked | 0x1c4 | 1 |  |
| GrantedAbilitySpecs | 0x1c8 | 16 |  |
| EffectContext | 0x278 | 24 | GameplayEffectContextHandle |
| Level | 0x290 | 4 | PredictionKey |

## GameplayTag

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TagName | 0x0 | 8 | ModifierSpec |

## GameplayTagContainer

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GameplayTags | 0x0 | 16 |  |
| ParentTags | 0x10 | 16 |  |

## GaussianBlurEffectSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Weight | 0x0 | 4 | LensImperfectionSettings |

## GaussianSumBloomSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Intensity | 0x0 | 4 | GaussianSumBloomSettings |
| MaxLuminance | 0x4 | 4 | GaussianSumBloomSettings |
| MaxLuminanceWithoutExposure | 0x8 | 4 | GaussianSumBloomSettings |
| MaxLuminanceWithoutExposureEnabled | 0xc | 1 |  |
| Threshold | 0x10 | 4 | GaussianSumBloomSettings |
| SizeScale | 0x14 | 4 | GaussianSumBloomSettings |
| Filter1Size | 0x18 | 4 | GaussianSumBloomSettings |
| Filter2Size | 0x1c | 4 | GaussianSumBloomSettings |
| Filter3Size | 0x20 | 4 |  |
| Filter4Size | 0x24 | 4 | GaussianSumBloomSettings |
| Filter5Size | 0x28 | 4 | GaussianSumBloomSettings |
| Filter6Size | 0x2c | 4 | ConvolutionBloomSettings |
| Filter1Tint | 0x30 | 16 | LinearColor |
| Filter2Tint | 0x40 | 16 | LinearColor |
| Filter3Tint | 0x50 | 16 | LinearColor |
| Filter4Tint | 0x60 | 16 | LinearColor |
| Filter5Tint | 0x70 | 16 | LinearColor |
| Filter6Tint | 0x80 | 16 | LinearColor |

## GeneAtlasParamVsAtlasMap

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ChannelUsage | 0x0 | 96 | GeneBatchTextureChannelUsage |
| AtlasGuid | 0x60 | 16 | Guid |
| AtlasMapIndex | 0x70 | 4 | MaterialParameterValue |

## GeneAtlasResultAtlas

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OwnerGroupGuid | 0x0 | 16 | Guid |
| AssetNum | 0x10 | 4 | GeneAtlasResultAtlas |
| ChannelUsage | 0x18 | 96 | GeneBatchTextureChannelUsage |
| maps | 0x78 | 16 |  |
| BakeMethod | 0x88 | 1 | EGeneBatchBakeMethod |
| TextureAtlasGuids | 0x90 | 16 |  |
| StrictAlignGroupIndex | 0xa0 | 4 | GeneBakeTableRowResultPrimitveTexture |

## GeneAtlasResultRegion

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x0 | 8 | IntPoint |
| Resolution | 0x8 | 8 | IntPoint |
| SourceTexture | 0x10 | 40 | Texture |
| SourceMipIndex | 0x38 | 4 | GeneBatchRuntimeMergingMeshInputElement |
| MaterialAtlasUsage | 0x3c | 1 | EMaterialAtlasUsage |
| InputTextureDataHash | 0x40 | 16 | Guid |

## GeneAtlasTableRowResultAtlasMaterialGroup

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Guid | 0x8 | 16 | Guid |
| ChannelUsageAtlases | 0x18 | 80 |  |
| AtlasGroupKey | 0x68 | 4 |  |
| bIgnoreAnisotropic | 0x6c | 1 |  |
| ForcePixelFormat | 0x6d | 1 | EPixelFormat |
| StrictAlignGroups | 0x70 | 16 |  |

## GeneBakeTableRowResultPrimitveTexture

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Atlas | 0x8 | 168 | GeneAtlasResultAtlas |
| MapIndex | 0xb0 | 4 | GeneAtlasResultRegion |
| Region | 0xb8 | 80 | GeneAtlasResultRegion |

## GeneBatchMaterialTextureParam

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TextureParamName | 0x0 | 8 | GeneBatchStaticMeshProxyInputElement |
| TextureGuid | 0x8 | 16 | Guid |

## GeneBatchMeshMapBuildDataKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bValid | 0x0 | 1 |  |
| LocalLightGroupBake | 0x4 | 8 |  |
| bLODsShareStaticLighting | 0xc | 1 |  |
| bEnableAOLightmap | 0xd | 1 |  |
| Textures | 0x10 | 16 |  |

## GeneBatchReflectionCaptureKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bOnlySkylight | 0x0 | 1 |  |
| bForceSkylightReflection | 0x1 | 1 |  |
| LocalReflectionGroupBake | 0x4 | 8 | CategoryStyleManualMapping |
| LocalReflectionGroupBakeBuildID | 0xc | 16 | Guid |

## GeneBatchRuntimeMergingMeshInputElement

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| IndexInStaticMeshTable | 0x0 | 4 | GeneBatchRuntimeMergingMeshInputElement |
| LodIndex | 0x4 | 4 | GeneBatchRuntimeMergingMeshInputElement |
| DrawSectionIndex | 0x8 | 4 | GeneBatchRuntimeMergingMeshInputElement |
| StaticMeshTransform | 0x10 | 48 | Transform |
| LocalMaterialIndex | 0x40 | 4 | GeneBatchRuntimeMergingMeshInputMergeDrawSection |
| bHasLightMap | 0x44 | 1 |  |
| CoordinateBias | 0x48 | 8 | Vector2D |
| CoordinateScale | 0x50 | 8 | Vector2D |

## GeneBatchRuntimeMergingMeshInputMergeDrawSection

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Elements | 0x0 | 16 |  |
| MaterialIndex | 0x10 | 4 | GeneBatchMaterialTextureParam |

## GeneBatchSMCProperties

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MeshMapBuildDataKey | 0x0 | 32 | GeneBatchMeshMapBuildDataKey |
| ReflectionCaptureKey | 0x20 | 28 | GeneBatchReflectionCaptureKey |
| bHiddenInGame | 0x3c | 1 |  |

## GeneBatchStaticMeshProxyInputElement

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| IndexInStaticMeshTable | 0x0 | 4 | GeneBatchStaticMeshProxyInputElement |
| LodIndex | 0x4 | 4 | GeneBatchTableRowWhyNotBatchComponentDetail |

## GeneBatchTableRowResourceConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Object | 0x8 | 40 | Object |
| TextureSize | 0x30 | 4 | GeneAtlasResultAtlas |

## GeneBatchTableRowWhyNotBatchComponentDetail

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Guid | 0x8 | 16 | Guid |
| Type | 0x18 | 1 | EGeneBatchWhyNotBatchDetailType |
| ParentGuid | 0x1c | 16 | Guid |
| HLODIndex | 0x2c | 4 |  |
| StaticMeshTags | 0x30 | 16 |  |
| ComponentTags | 0x40 | 16 |  |
| MeshName | 0x50 | 8 | GeneBatchTableRowWhyNotBatchComponentDetail |
| GridLevel | 0x58 | 8 | IntPoint |
| SMCProperties | 0x60 | 64 | GeneBatchSMCProperties |
| POI | 0xa0 | 8 | GeneBatchTableRowWhyNotBatchComponentDetail |
| LevelKey | 0xa8 | 16 | GeneBatchTableRowWhyNotBatchComponentDetail |
| VertexCount | 0xb8 | 4 | GeneBatchTableRowWhyNotBatchComponentDetail |
| BoundSize | 0xbc | 12 | Vector |
| LightMapUVRange | 0xc8 | 20 | Box2D |
| HLODLevel | 0xdc | 4 | GeneBatchTableRowWhyNotBatchComponentDetail |
| OriginalMeshKey | 0xe0 | 4 | GeneBatchTableRowWhyNotBatchComponentDetail |
| bUseOriginalMesh | 0xe4 | 1 |  |
| MaterialGroupKey | 0xe8 | 4 |  |
| OverrideMaterials | 0xf0 | 16 |  |
| VertexColorIndices | 0x100 | 16 |  |
| MergeMeshTypeKey | 0x110 | 4 | GeneBatchTableRowWhyNotBatchComponentDetail |
| ISMKey | 0x114 | 4 | GeneBatchTableRowWhyNotBatchComponentDetail |
| OriginalISMKey | 0x118 | 4 |  |
| bIgnoreTransform | 0x11c | 1 |  |
| bCastShadow | 0x11d | 1 |  |
| bCastDynamicShadow | 0x11e | 1 |  |
| bCastStaticShadow | 0x11f | 1 |  |
| bReuseMesh | 0x120 | 1 |  |
| Units | 0x128 | 16 |  |

## GeneBatchTextureBaseChannelUsage

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ChannelUsageName | 0x0 | 8 | GeneAtlasParamVsAtlasMap |
| MaterialAtlasUsage | 0x8 | 1 | EMaterialAtlasUsage |
| bUseAlpha | 0x9 | 1 |  |
| bForceLinearColor | 0xa | 1 |  |
| bAnisotropic | 0xb | 1 |  |

## GeneBatchTextureChannelUsage

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PlatformPixelFormats | 0x10 | 80 |  |

## GlobalInteriorFogData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InteriorFogMaterial | 0x0 | 8 | MaterialInterface |
| Albedo | 0x8 | 16 | LinearColor |
| ExtinctionScale | 0x18 | 4 | GlobalInteriorFogData |
| ViewDistance | 0x1c | 4 | GlobalInteriorFogData |
| ExcludeRange | 0x20 | 4 | GlobalInteriorFogData |
| ExcludeOpacity | 0x24 | 4 | GlobalInteriorFogData |
| ExtendVisibleDistance | 0x28 | 4 | CurveEdTab |

## GridBlendSample

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GridElement | 0x0 | 24 | EditorElement |
| BlendWeight | 0x18 | 4 | PerBoneInterpolation |

## Guid

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| A | 0x0 | 4 | Guid |
| B | 0x4 | 4 | Guid |
| C | 0x8 | 4 | Guid |
| D | 0xc | 4 | JoinabilitySettings |

## HitResult

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bBlockingHit | 0x0 | 1 |  |
| bStartPenetrating | 0x0 | 1 |  |
| FaceIndex | 0x4 | 4 | HitResult |
| Time | 0x8 | 4 | HitResult |
| Distance | 0xc | 4 | HitResult |
| Location | 0x10 | 12 | Vector_NetQuantize |
| ImpactPoint | 0x1c | 12 | Vector_NetQuantize |
| Normal | 0x28 | 12 | Vector_NetQuantizeNormal |
| ImpactNormal | 0x34 | 12 | Vector_NetQuantizeNormal |
| TraceStart | 0x40 | 12 | Vector_NetQuantize |
| TraceEnd | 0x4c | 12 | Vector_NetQuantize |
| PenetrationDepth | 0x58 | 4 | HitResult |
| Item | 0x5c | 4 | HitResult |
| PhysMaterial | 0x60 | 8 | PhysicalMaterial |
| Actor | 0x68 | 8 | Actor |
| Component | 0x70 | 8 | PrimitiveComponent |
| BoneName | 0x78 | 8 | HitResult |
| MyBoneName | 0x80 | 8 |  |

## ImportFactorySettingValues

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SettingName | 0x0 | 16 | ImportFactorySettingValues |
| Value | 0x10 | 16 | BuildPromotionNewProjectSettings |

## IndexedCurve

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| KeyHandlesToIndices | 0x8 | 96 | KeyHandleMap |

## Info

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## InputActionSpeechMapping

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ActionName | 0x0 | 8 | GaussianSumBloomSettings |
| SpeechKeyword | 0x8 | 8 | UpdateLevelStreamingLevelStatus |

## Int32Interval

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Min | 0x0 | 4 | Int32Interval |
| Max | 0x4 | 4 | FloatInterval |

## Int32RangeBound

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Type | 0x0 | 1 | ERangeBoundTypes |
| Value | 0x4 | 4 | FloatRangeBound |

## Int32Vector4

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | Int32Vector4 |
| Y | 0x4 | 4 | Int32Vector4 |
| Z | 0x8 | 4 | Int32Vector4 |
| W | 0xc | 4 | CapsuleShape |

## Int64Vector4

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 8 | Int64Vector4 |
| Y | 0x8 | 8 | Int64Vector4 |
| Z | 0x10 | 8 |  |
| W | 0x18 | 8 | Int32Vector4 |

## IntCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bEnableInterpolate | 0x798 | 1 |  |
| bEnableExtrapolate | 0x798 | 1 |  |
| bIsProned | 0x7a0 | 4 | TurningPlaceData |
| bIsSupined | 0x7a4 | 1 |  |
| bIsJumped | 0x7a4 | 1 |  |
| bIsJumpedOverride | 0x7a4 | 1 |  |
| RepTurningPlaceData | 0x7a8 | 8 | TurningPlaceData |
| RepStartStopData | 0x7b0 | 40 | StartStopData |
| DisableBitArray | 0x7e8 | 32 | ExplicitDisableBitArray |
| CosmeticData_Server_Character_OnFire | 0x818 | 248 | NetworkCosmeticData_Server_Character_OnFire |
| bA | 0x9f4 | 1 |  |
| MoveHandle | 0x9f8 | 4 | CharacterMoveHandle |
| AutonomousMovementInfo | 0xa1c | 56 | RepMovement |

## IntPoint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | IntPoint |
| Y | 0x4 | 4 | PackedRGBA16N |

## IntVector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | IntVector |
| Y | 0x4 | 4 | IntVector |
| Z | 0x8 | 4 | Int64Vector4 |

## IntegralCurve

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Keys | 0x68 | 16 |  |
| DefaultValue | 0x78 | 4 |  |
| bUseDefaultValueBeforeFirstKey | 0x7c | 1 |  |

## IntegralKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Time | 0x0 | 4 | IntegralKey |
| Value | 0x4 | 4 | IntegralCurve |

## InteriorSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bIsWorldSettings | 0x0 | 1 |  |
| ExteriorVolume | 0x4 | 4 | InteriorSettings |
| ExteriorTime | 0x8 | 4 | InteriorSettings |
| ExteriorLPF | 0xc | 4 | CachedAnimRelevancyData |
| ExteriorLPFTime | 0x10 | 4 | InteriorSettings |
| InteriorVolume | 0x14 | 4 | InteriorSettings |
| InteriorTime | 0x18 | 4 | InteriorSettings |
| InteriorLPF | 0x1c | 4 | InteriorSettings |
| InteriorLPFTime | 0x20 | 4 | AudioQualitySettings |

## InterpCurveFloat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Points | 0x0 | 16 |  |
| bIsLooped | 0x10 | 1 |  |
| LoopKeyOffset | 0x14 | 4 | InterpCurvePointFloat |

## InterpCurveLinearColor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Points | 0x0 | 16 |  |
| bIsLooped | 0x10 | 1 |  |
| LoopKeyOffset | 0x14 | 4 | InterpCurvePointLinearColor |

## InterpCurvePointFloat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InVal | 0x0 | 4 | InterpCurvePointFloat |
| OutVal | 0x4 | 4 | InterpCurvePointFloat |
| ArriveTangent | 0x8 | 4 | InterpCurvePointFloat |
| LeaveTangent | 0xc | 4 | OrientedBox |
| InterpMode | 0x10 | 1 | EInterpCurveMode |

## InterpCurvePointLinearColor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InVal | 0x0 | 4 | InterpCurveTwoVectors |
| OutVal | 0x4 | 16 | LinearColor |
| ArriveTangent | 0x14 | 16 | LinearColor |
| LeaveTangent | 0x24 | 16 | LinearColor |
| InterpMode | 0x34 | 1 | EInterpCurveMode |

## InterpCurvePointQuat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InVal | 0x0 | 4 | InterpCurveVector |
| OutVal | 0x10 | 16 | Quat |
| ArriveTangent | 0x20 | 16 | Quat |
| LeaveTangent | 0x30 | 16 | Quat |
| InterpMode | 0x40 | 1 | EInterpCurveMode |

## InterpCurvePointTwoVectors

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InVal | 0x0 | 4 | InterpCurveQuat |
| OutVal | 0x4 | 24 | TwoVectors |
| ArriveTangent | 0x1c | 24 | TwoVectors |
| LeaveTangent | 0x34 | 24 | TwoVectors |
| InterpMode | 0x4c | 1 | EInterpCurveMode |

## InterpCurvePointVector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InVal | 0x0 | 4 | InterpCurveVector2D |
| OutVal | 0x4 | 12 | Vector |
| ArriveTangent | 0x10 | 12 | Vector |
| LeaveTangent | 0x1c | 12 | Vector |
| InterpMode | 0x28 | 1 | EInterpCurveMode |

## InterpCurvePointVector2D

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InVal | 0x0 | 4 | InterpCurveFloat |
| OutVal | 0x4 | 8 | Vector2D |
| ArriveTangent | 0xc | 8 | Vector2D |
| LeaveTangent | 0x14 | 8 | Vector2D |
| InterpMode | 0x1c | 1 | EInterpCurveMode |

## InterpCurveQuat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Points | 0x0 | 16 |  |
| bIsLooped | 0x10 | 1 |  |
| LoopKeyOffset | 0x14 | 4 | InterpCurvePointQuat |

## InterpCurveTwoVectors

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Points | 0x0 | 16 |  |
| bIsLooped | 0x10 | 1 |  |
| LoopKeyOffset | 0x14 | 4 | InterpCurvePointTwoVectors |

## InterpCurveVector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Points | 0x0 | 16 |  |
| bIsLooped | 0x10 | 1 |  |
| LoopKeyOffset | 0x14 | 4 | InterpCurvePointVector |

## InterpCurveVector2D

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Points | 0x0 | 16 |  |
| bIsLooped | 0x10 | 1 |  |
| LoopKeyOffset | 0x14 | 4 | InterpCurvePointVector2D |

## InterpolationParameter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InterpolationTime | 0x0 | 4 | BlendParameter |
| InterpolationType | 0x4 | 1 | EFilterInterpolationType |

## IrisWorldGameState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TeamLeaderID | 0xfb8 | 8 |  |
| m_ResStates | 0xfc0 | 80 |  |
| ResPlayerID | 0x1010 | 8 |  |
| RaidMatchPlayerIDs | 0x1018 | 16 |  |
| IsTeammateAllDied | 0x1028 | 1 |  |
| CurGameFlowState | 0x1030 | 16 |  |
| CurGameRuleType | 0x1040 | 1 | EGameRuleType |
| ClientIrisWorldTeamAllDiedStatusChangedEvent | 0x1048 | 16 |  |
| TimeLineEventComponent | 0x1058 | 8 | SOLTimeLineComponnet |
| IrisRaidDataStatisticsComponent | 0x1060 | 8 | IrisRaidDataStatisticsComponent |
| ContractManagerComponent | 0x1068 | 8 | DFMContractManagerComponent |
| PerfGroupName | 0x1070 | 1 | EGPPrefGroupName |

## J3PastaWindLevelParameter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EnableSoftBone | 0x0 | 1 |  |
| Softness | 0x4 | 4 | J3PastaWindLevelParameter |
| Heaviness | 0x8 | 4 | J3PastaWindLevelParameter |
| MaxBendAngle | 0xc | 4 | J3PastaWindLevelParameter |
| MaxSwayAngle | 0x10 | 4 | J3PastaWindLevelParameter |
| RandomSwayIntensity | 0x14 | 4 | J3PastaWindLevelParameter |
| SoftBoneFalloff | 0x18 | 4 | VisibilityTrackKey |

## JoinabilitySettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SessionName | 0x0 | 8 | FrameTime |
| bPublicSearchable | 0x8 | 1 |  |
| bAllowInvites | 0x9 | 1 |  |
| bJoinViaPresence | 0xa | 1 |  |
| bJoinViaPresenceFriendsOnly | 0xb | 1 |  |
| MaxPlayers | 0xc | 4 |  |
| MaxPartySize | 0x10 | 4 |  |

## KantanCategoryStyle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CategoryStyleId | 0x0 | 8 | CartesianAxisRange |
| Color | 0x8 | 16 | LinearColor |

## KantanSeriesStyle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StyleId | 0x0 | 8 | GeneAtlasTableRowResultAtlasMaterialGroup |
| PointStyle | 0x8 | 8 | KantanPointStyle |
| Color | 0x10 | 16 | LinearColor |

## KeyHandleMap

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## KillInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| KillerUin | 0x18 | 8 |  |
| InstigatorUin | 0x20 | 8 | KillInfo |
| MineShooterUin | 0x28 | 8 | KillInfo |
| KillerWeaponID | 0x30 | 8 | KillInfo |
| KillerShowWeaponID | 0x38 | 8 | KillInfo |
| KillerShowWeaponGID | 0x40 | 8 | KillInfo |
| KillerWeaponGID | 0x48 | 8 | KillInfo |
| KillerSkillID | 0x50 | 4 | KillInfo |
| KillerSkillEntityID | 0x54 | 4 | KillInfo |
| KillerVehicleID | 0x58 | 4 |  |
| bKillerInVehicleLeanOut | 0x5c | 1 |  |
| KillerWeaponType | 0x5d | 1 | EWeaponItemType |
| KillerWeaponModuleID | 0x60 | 16 |  |
| BeKilledUin | 0x70 | 8 | KillInfo |
| BeKilledType | 0x78 | 1 | EDeadType |
| KillDistance | 0x7c | 4 | KillInfo |
| MakerLocation | 0x80 | 12 | Vector |
| MakerIsPlayer | 0x8c | 1 |  |
| MakerIsAILAB | 0x8d | 1 |  |
| MakerIsRobotAI | 0x8e | 1 |  |
| MakerIsAIBoss | 0x8f | 1 |  |
| TakerLocation | 0x90 | 12 | Vector |
| TakerIsPlayer | 0x9c | 1 |  |
| TakerIsAILAB | 0x9d | 1 |  |
| TakerIsRobotAI | 0x9e | 1 |  |
| TakerIsAIBoss | 0x9f | 1 |  |
| IsHitHead | 0xa0 | 1 |  |
| LastHitPosition | 0xa1 | 1 |  |
| LastHitAmount | 0xa4 | 4 | KillInfo |
| BeKilledName | 0xa8 | 24 | KillInfo |
| KillerName | 0xc0 | 24 | KillInfo |
| InstigatorName | 0xd8 | 24 | KillInfo |
| BeKilledLocation | 0xf0 | 12 | Vector |
| KillTime | 0xfc | 4 | KillInfo |
| KillerAmmoId | 0x100 | 8 | KillInfo |
| AttackLevel | 0x108 | 4 | KillInfo |
| bIsKnockDown | 0x10c | 1 |  |
| bDirectDead | 0x10d | 1 |  |
| TakerDeadTickNum | 0x110 | 4 | KillInfo |
| TeamId1 | 0x114 | 4 | KillInfo |
| TeamId2 | 0x118 | 4 | KillInfo |
| BuffId | 0x11c | 4 | KillInfo |
| BeKilledCampId | 0x120 | 4 | KillInfo |
| KillerCampId | 0x124 | 4 | KillInfo |
| DamageTags | 0x128 | 32 | GameplayTagContainer |
| AttackValueId | 0x148 | 8 |  |
| BeKilledCharacter | 0x150 | 8 | GPCharacterBase |
| KillerCharacter | 0x158 | 8 | GPCharacterBase |
| AssistPlayerIds | 0x160 | 16 |  |
| bKillTeam | 0x180 | 1 |  |
| InPOINameLocalizedKey | 0x188 | 16 |  |
| ComboCount | 0x1a8 | 4 | ModularWeaponDynamicAttrbuites |
| bKillerIsVIP | 0x1ac | 1 |  |
| bBeKilledIsVIP | 0x1ad | 1 |  |

## LandscapeLayer

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Guid | 0x0 | 16 | Guid |
| Name | 0x10 | 8 | LandscapeLayer |
| bVisible | 0x18 | 1 |  |
| bIsAdditiveLayer | 0x19 | 1 |  |
| bStoreInPatch | 0x1a | 1 |  |
| bLocked | 0x1b | 1 |  |
| HeightmapAlpha | 0x1c | 4 | LandscapeLayer |
| WeightmapAlpha | 0x20 | 4 |  |
| BlendMode | 0x24 | 1 | ELandscapeBlendMode |
| Brushes | 0x28 | 16 |  |
| WeightmapLayerAllocationBlend | 0x38 | 80 |  |

## LandscapeLayerTillingsValue

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LayerTilling | 0x0 | 4 | ExtraOutputPin |

## LaunchOnTestSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LaunchOnTestmap | 0x0 | 16 | FilePath |
| DeviceID | 0x10 | 16 | ReverbSettings |

## LayerActorStats

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Type | 0x0 | 8 | Class |
| Total | 0x8 | 4 | J3PastaWindLevelParameter |

## LensBloomSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GaussianSum | 0x0 | 144 | GaussianSumBloomSettings |
| Convolution | 0x90 | 40 | ConvolutionBloomSettings |
| Method | 0xb8 | 1 | EBloomMethod |

## LensImperfectionSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DirtMask | 0x0 | 8 | Texture |
| DirtMaskIntensity | 0x8 | 4 | LensSettings |
| DirtMaskTint | 0xc | 16 | LinearColor |

## LensSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Bloom | 0x0 | 192 | LensBloomSettings |
| Blur | 0xc0 | 8 | PostProcessBlurEffectSettings |
| Imperfections | 0xc8 | 32 | LensImperfectionSettings |
| ChromaticAberration | 0xe8 | 4 | CameraExposureSettings |

## LevelSimplificationDetails

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bCreatePackagePerAsset | 0x0 | 1 |  |
| DetailsPercentage | 0x4 | 4 | LevelSimplificationDetails |
| StaticMeshMaterialSettings | 0x8 | 172 | MaterialProxySettings |
| bOverrideLandscapeExportLOD | 0xb4 | 1 |  |
| LandscapeExportLOD | 0xb8 | 4 | MaterialProxySettings |
| LandscapeMaterialSettings | 0xbc | 172 | MaterialProxySettings |
| bBakeFoliageToLandscape | 0x168 | 1 |  |
| bBakeGrassToLandscape | 0x169 | 1 |  |
| bGenerateMeshNormalMap | 0x16a | 1 |  |
| bGenerateMeshMetallicMap | 0x16b | 1 |  |
| bGenerateMeshRoughnessMap | 0x16c | 1 |  |
| bGenerateMeshSpecularMap | 0x16d | 1 |  |
| bGenerateLandscapeNormalMap | 0x16e | 1 |  |
| bGenerateLandscapeMetallicMap | 0x16f | 1 |  |
| bGenerateLandscapeRoughnessMap | 0x170 | 1 |  |
| bGenerateLandscapeSpecularMap | 0x171 | 1 |  |

## LevelStreamingStatus

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PackageName | 0x0 | 8 | LevelStreamingStatus |
| bShouldBeLoaded | 0x8 | 1 |  |
| bShouldBeVisible | 0x8 | 1 |  |
| LodIndex | 0xc | 4 | WorldContext |

## LightImportanceAssetData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LightGuid | 0x0 | 16 | Guid |
| Importance | 0x10 | 4 | PrecomputedLightInstanceData |

## LightMapAtlasPackingSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LightMapGroupingPolicy | 0x0 | 1 | ELightMapGroupingPolicy |
| LightMapAllocationPolicy | 0x1 | 1 | ELightMapAllocationPolicy |
| bPackAndNoBaking | 0x2 | 1 |  |
| TotalLightMapCount | 0x4 | 4 | AnimUpdateRateParameters |
| TexelPerMeter | 0x8 | 4 | LightMapAtlasPackingSettings |
| MinTexelPerTriangle | 0xc | 4 | LightMapAtlasPackingSettings |
| GlobalLODLightMapScaleFactor | 0x10 | 4 | LightMapAtlasPackingSettings |
| MaxLightMapResolution | 0x14 | 4 | LightMapAtlasPackingSettings |
| AtlasPaddingPixels | 0x18 | 4 | LightMapAtlasPackingSettings |
| LightMapMarginPixels | 0x1c | 4 | ExposureSettings |

## LightmassDebugOptions

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bDebugMode | 0x0 | 1 |  |
| bStatsEnabled | 0x0 | 1 |  |
| bGatherBSPSurfacesAcrossComponents | 0x0 | 1 |  |
| CoplanarTolerance | 0x4 | 4 | LightmassDebugOptions |
| bUseImmediateImport | 0x8 | 1 |  |
| bImmediateProcessMappings | 0x8 | 1 |  |
| bSortMappings | 0x8 | 1 |  |
| bDumpBinaryFiles | 0x8 | 1 |  |
| bDebugMaterials | 0x8 | 1 |  |
| bPadMappings | 0x8 | 1 |  |
| bDebugPaddings | 0x8 | 1 |  |
| bOnlyCalcDebugTexelMappings | 0x8 | 1 |  |
| bUseRandomColors | 0x9 | 1 |  |
| bColorBordersGreen | 0x9 | 1 |  |
| bColorByExecutionTime | 0x9 | 1 |  |
| ExecutionTimeDivisor | 0xc | 4 | PrimitiveMaterialRef |

## LightmassDirectionalLightSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LightSourceAngle | 0xc | 4 | LightmassLightSettings |

## LightmassLightSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| IndirectLightingSaturation | 0x0 | 4 | LightmassLightSettings |
| ShadowExponent | 0x4 | 4 | LightmassPrimitiveSettings |
| bUseAreaShadowsForStationaryLight | 0x8 | 1 |  |

## LightmassMaterialInterfaceSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EmissiveBoost | 0x0 | 4 | NodeItem |
| DiffuseBoost | 0x4 | 4 | LightmassMaterialInterfaceSettings |
| ExportResolutionScale | 0x8 | 4 | FontParameterValue |
| bCastShadowAsMasked | 0xc | 1 |  |
| bOverrideCastShadowAsMasked | 0xc | 1 |  |
| bOverrideEmissiveBoost | 0xc | 1 |  |
| bOverrideDiffuseBoost | 0xc | 1 |  |
| bOverrideExportResolutionScale | 0xc | 1 |  |
| bOverrideExportAsLightmapUV | 0xc | 1 |  |
| bExportAsLightmapUV | 0xc | 1 |  |
| bOverrideForceNoExportAsLightmapUV | 0xc | 1 |  |
| bForceNoExportAsLightmapUV | 0xd | 1 |  |

## LightmassPrimitiveSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bUseTwoSidedLighting | 0x0 | 1 |  |
| bShadowIndirectOnly | 0x0 | 1 |  |
| bUseEmissiveForStaticLighting | 0x0 | 1 |  |
| bUseVertexNormalForHemisphereGather | 0x0 | 1 |  |
| EmissiveLightFalloffExponent | 0x4 | 4 | LightmassPrimitiveSettings |
| EmissiveLightExplicitInfluenceRadius | 0x8 | 4 | LightmassPrimitiveSettings |
| EmissiveBoost | 0xc | 4 | LightmassPrimitiveSettings |
| EmissiveAttenuationRadius | 0x10 | 4 | LightmassPrimitiveSettings |
| DiffuseBoost | 0x14 | 4 | LightmassPrimitiveSettings |
| FullyOccludedSamplesFraction | 0x18 | 4 | LightmassDebugOptions |
| bJoinLocalLightBake | 0x1c | 1 |  |
| bIgnoreBounds | 0x1c | 1 |  |

## LinearColor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| R | 0x0 | 4 | LinearColor |
| G | 0x4 | 4 | LinearColor |
| B | 0x8 | 4 | LinearColor |
| A | 0xc | 4 | IntVector |

## LinearConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Limit | 0x14 | 4 | ConeConstraint |
| XMotion | 0x18 | 1 | ELinearConstraintMotion |
| YMotion | 0x19 | 1 | ELinearConstraintMotion |
| ZMotion | 0x1a | 1 | ELinearConstraintMotion |

## LinearDriveConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PositionTarget | 0x0 | 12 | Vector |
| VelocityTarget | 0xc | 12 | Vector |
| XDrive | 0x18 | 16 | ConstraintDrive |
| YDrive | 0x28 | 16 | ConstraintDrive |
| ZDrive | 0x38 | 16 | ConstraintDrive |
| bEnablePositionDrive | 0x48 | 1 |  |

## LuaFileTag

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LuaFilePath | 0x0 | 16 | ReplifetimeCond |

## MapAreaInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AreaName | 0x10 | 16 | MapAreaInfo |
| AreaId | 0x20 | 4 | SOLExitConfig |
| Precompile | 0x24 | 1 |  |
| WorldScale | 0x25 | 1 | EWorldScale |
| AreaNameCheckContain | 0x26 | 1 |  |

## MapConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MapID | 0x10 | 4 | MapConfig |
| DisplayName | 0x18 | 24 | MapConfig |
| LevelName | 0x30 | 16 | MapConfig |
| SubWorldName | 0x40 | 16 | MapConfig |
| LevelFullPath | 0x50 | 16 |  |
| TargetKillCount | 0x60 | 4 | MapConfig |
| MaxMatchDuration | 0x64 | 4 | MapConfig |
| bAddToCook | 0x68 | 1 |  |
| bShowInMapSelection | 0x69 | 1 |  |
| bUseFastNetFrame | 0x6a | 1 |  |
| MapDesc | 0x70 | 24 | MapConfig |
| bStreamingLevel | 0x88 | 1 |  |
| bUsePSOCache | 0x89 | 1 |  |
| bInGameLevel | 0x8a | 1 |  |
| bShouldWaitingAllPlayerLoadComplete | 0x8b | 1 |  |
| DoorKeyConsumeMultiple | 0x8c | 4 | MapAreaInfo |

## MapFloorCaptureInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FloorType | 0x0 | 1 | EMapFloorType |
| FloorWidth | 0x4 | 4 |  |
| CapturePointIndexArr | 0x8 | 16 |  |
| CapturePointTexNameArr | 0x18 | 16 |  |
| MapFloorVolume | 0x28 | 8 | MapFloorVolume |

## MapGlitchEffectConfigRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MapID | 0x8 | 4 |  |
| bEnableMapGlitchEffect | 0xc | 1 |  |
| ExcludeCampIds | 0x10 | 16 |  |

## Margin

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Left | 0x0 | 4 | Margin |
| Top | 0x4 | 4 | Margin |
| Right | 0x8 | 4 | Margin |
| Bottom | 0xc | 4 | SlateBrush |

## MarkerCampTeamId

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CampId | 0x0 | 4 | MarkerCampTeamId |
| TeamID | 0x4 | 4 | MarkingAnimData |

## MarkerCoordinatedStruct

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkedActor | 0x0 | 8 | Actor |
| ActorID | 0x8 | 8 | GPLuaQuestData |
| CurMarkerCoordinatedTypes | 0x10 | 80 |  |

## MarkerItemCreateConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkerItemClassBPClass | 0x8 | 40 | Class |
| MarkerConfig | 0x30 | 40 | GPMarkerConfigDataAsset |
| MarkerExtraConfig | 0x58 | 40 | MarkerConfigExtraDataAsset |
| LowLevelMarkerConfig | 0x80 | 40 | GPMarkerConfigDataAsset |
| LowLevelMarkerExtraConfig | 0xa8 | 40 | MarkerConfigExtraDataAsset |
| AllowCreateGameplayModes | 0xd0 | 16 |  |
| GameMarkerFeature | 0xe0 | 8 | BattleFieldMarkingViewInfo |

## MarkerViewCreateConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CreatedDistance | 0x0 | 4 | MarkerViewCreateConfig |
| bHideWhenOutScreen | 0x4 | 1 |  |
| bHideWhenCovered | 0x5 | 1 |  |
| bForceShowWithinDistance | 0x6 | 1 |  |
| ForceShowDistance | 0x8 | 4 | MarkerViewCreateConfig |
| bShowWithinDistance | 0xc | 1 |  |
| ShowDistance | 0x10 | 4 | MarkerViewCreateConfig |
| AimCheckDistance | 0x14 | 4 |  |
| bHideWhenNotAimed | 0x18 | 1 |  |
| bHideWhenNotInAimedCircle | 0x19 | 1 |  |
| AimedCircleRadiusFactorArray | 0x20 | 16 |  |
| AimedCircleRadiusAimingOpacityArray | 0x30 | 16 |  |
| AimedCircleRadiusNotAimingOpacityArray | 0x40 | 16 |  |
| bScreenSpaceAimed | 0x50 | 1 |  |
| bScaleWithDistance | 0x51 | 1 |  |
| ScaleDistanceArray | 0x58 | 16 |  |
| ScaleScalarArray | 0x68 | 16 |  |
| bOutScreenOverrideScale | 0x78 | 1 |  |
| OutScreenOverrideScale | 0x7c | 4 | MarkerViewCreateConfig |
| bOwnerPlayMarkingEffect | 0x80 | 1 |  |
| bOtherPlayMarkingEffect | 0x81 | 1 |  |
| bOwnerMarkingEffectLast | 0x82 | 1 |  |
| bOtherMarkingEffectLast | 0x83 | 1 |  |
| bEnableOpacityChange | 0x84 | 1 |  |
| NormalOpacity | 0x88 | 4 | MarkerViewCreateConfig |
| CoveredOpacity | 0x8c | 4 | MarkerViewCreateConfig |
| AimingOpacity | 0x90 | 4 | MarkerViewCreateConfig |
| bOutScreenOverrideOpacity | 0x94 | 1 |  |
| OutScreenOverrideOpacity | 0x98 | 4 |  |
| bEnableOpacityDistance | 0x9c | 1 |  |
| OpacityDistanceArray | 0xa0 | 16 |  |
| OpacityScalarArray | 0xb0 | 16 |  |
| bNeedShowDistanceText | 0xc0 | 1 |  |
| bShowDistanceDefault | 0xc1 | 1 |  |
| bShowDistanceWhenAiming | 0xc2 | 1 |  |
| bHideDistanceWhenCovered | 0xc3 | 1 |  |
| MaxDistanceShowDistance | 0xc4 | 4 | MarkerItemCreateConfig |
| bHideDistanceWhenOutScreen | 0xc8 | 1 |  |
| bShowDistanceWhenMarked | 0xc9 | 1 |  |
| bNeedHideMarkerWhenImpendingDeath | 0xca | 1 |  |
| bNeedShowArrow | 0xcb | 1 |  |
| MarkerEdgeTrackType | 0xcc | 1 | EMarkerEdgeTrackType |
| SceneMarkerOffset | 0xd0 | 12 | Vector |

## MarkingAnimData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkingAnimWidgetClass | 0x0 | 8 | Class |
| AnimName_Marking | 0x8 | 8 | MarkingAnimData |
| bAnimLoop | 0x10 | 1 |  |
| AnimLoopIntervalTime | 0x14 | 4 | MarkingAnimData |
| MarkingSoundName | 0x18 | 16 | MarkerCoordinatedStruct |
| MarkingColor | 0x28 | 16 | LinearColor |
| MarkerAnchorData | 0x38 | 40 | AnchorData |

## MarkingAnimDataInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MarkingAnimWidgetClass | 0x0 | 40 | Class |
| AnimName_Marking | 0x28 | 8 | MarkingAnimDataInfo |
| bAnimLoop | 0x30 | 1 |  |
| AnimName_MarkingLoop | 0x34 | 8 |  |
| AnimLoopIntervalTime | 0x3c | 4 | MarkingAnimDataInfo |
| MarkingSoundName | 0x40 | 16 | BreakThroughTacticalMarkingRow |
| MarkingColor | 0x50 | 16 | LinearColor |

## MatchInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ModeType | 0x0 | 1 | EModeType |
| TeamType | 0x1 | 1 | ETeamType |
| MatchType | 0x2 | 1 | EMatchType |
| MatchGameMode | 0x4 | 4 | MatchInfo |
| MatchGameRule | 0x8 | 1 | EGameRuleType |
| MatchSubType | 0x9 | 1 | EMatchSubType |
| MatchSolMode | 0xa | 1 | EMatchSOLOMode |
| MapID | 0x10 | 8 | MatchInfo |
| RoomId | 0x18 | 8 | MatchInfo |
| AILevel | 0x20 | 4 | MatchInfo |
| MatchStartTimestamp | 0x28 | 8 | MatchInfo |
| MatchStartPhaseId | 0x30 | 4 | MatchInfo |
| bTournamentMatch | 0x38 | 1 |  |
| WeatherID | 0x68 | 8 | WeatherSwitchData |
| WeatherSwitchHistory | 0x70 | 16 |  |
| TODEventConfigId | 0x80 | 8 | MatchInfo |
| EventScriptId | 0x88 | 4 | MatchInfo |
| MapDropId | 0x8c | 4 | MatchInfo |
| MapLevel | 0x90 | 4 |  |
| HolidayActivityArray | 0x98 | 16 |  |
| LobbyServerTime | 0xa8 | 8 | MatchInfo |
| OpenAllExit | 0xb0 | 1 |  |
| ExitSwitchNum | 0xb4 | 4 | MatchInfo |
| CourseId | 0xb8 | 4 | MatchInfo |
| SpawnBossRule | 0xbc | 4 |  |
| WeaponBlueprintSpawnIDArray | 0xc0 | 16 |  |
| MandelBrickID | 0xd0 | 8 | MatchInfo |
| AIDropId | 0xd8 | 4 |  |
| EventIds | 0xe0 | 16 |  |
| HolidayArray | 0xf0 | 16 |  |
| DropDsTglogNameArray | 0x100 | 16 |  |
| SrcGameRule | 0x110 | 4 | MatchInfo |
| SrcMatchModeId | 0x114 | 4 | MatchInfo |
| SrcSubMode | 0x118 | 4 | MatchInfo |
| bIsVictoryUniteMatch | 0x11c | 1 |  |
| bExtremeIsolateType | 0x11d | 1 |  |
| bUseCustomStartSpot | 0x11e | 1 |  |
| RoomRoundNum | 0x120 | 4 | MapFloorCaptureInfo |

## MaterialCluster

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TargetSectionIndex | 0x0 | 4 |  |
| SourceSectionIndexArray | 0x8 | 16 |  |

## MaterialInput

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OutputIndex | 0x0 | 4 | MaterialInput |
| ExpressionName | 0x4 | 8 | PlatformInterfaceData |

## MaterialParameterInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | MaterialParameterInfo |
| Association | 0x8 | 1 | EMaterialParameterAssociation |
| Index | 0xc | 4 | GeneBatchTableRowResourceConfig |

## MaterialParameterValue

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ScalarValue | 0x0 | 4 | MaterialParameterValue |
| VectorValue | 0x4 | 16 | LinearColor |
| ObjectValue | 0x14 | 8 | MaterialParameterValue |
| UIntValue | 0x1c | 4 |  |
| ParameterType | 0x20 | 1 | EMaterialParameterDataType |

## MaterialProxySettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TextureSize | 0x0 | 8 | IntPoint |
| GutterSpace | 0x8 | 4 | MaterialProxySettings |
| MetallicConstant | 0xc | 4 | MaterialProxySettings |
| RoughnessConstant | 0x10 | 4 | MaterialProxySettings |
| AnisotropyConstant | 0x14 | 4 | MaterialProxySettings |
| SpecularConstant | 0x18 | 4 | MaterialProxySettings |
| OpacityConstant | 0x1c | 4 | MaterialProxySettings |
| OpacityMaskConstant | 0x20 | 4 | MaterialProxySettings |
| AmbientOcclusionConstant | 0x24 | 4 | MaterialProxySettings |
| WetnessMaskConstant | 0x28 | 4 | MaterialProxySettings |
| PorosityConstant | 0x2c | 4 | MaterialProxySettings |
| PuddleMaskConstant | 0x30 | 4 | LayerActorStats |
| TextureSizingType | 0x34 | 1 | ETextureSizingType |
| MaterialMergeType | 0x35 | 1 | EMaterialMergeType |
| BlendMode | 0x36 | 1 | EBlendMode |
| WetnessMode | 0x37 | 1 | EMaterialWetnessMode |
| bAllowTwoSidedMaterial | 0x38 | 1 |  |
| bNormalMap | 0x38 | 1 |  |
| bTangentMap | 0x38 | 1 |  |
| bMetallicMap | 0x38 | 1 |  |
| bRoughnessMap | 0x38 | 1 |  |
| bAnisotropyMap | 0x38 | 1 |  |
| bSpecularMap | 0x38 | 1 |  |
| bEmissiveMap | 0x38 | 1 |  |
| bOpacityMap | 0x39 | 1 |  |
| bOpacityMaskMap | 0x39 | 1 |  |
| bAmbientOcclusionMap | 0x39 | 1 |  |
| bWetnessMaskMap | 0x39 | 1 |  |
| bPorosityMap | 0x39 | 1 |  |
| bPuddleMaskMap | 0x39 | 1 |  |
| DiffuseTextureSize | 0x3c | 8 | IntPoint |
| NormalTextureSize | 0x44 | 8 | IntPoint |
| TangentTextureSize | 0x4c | 8 | IntPoint |
| MetallicTextureSize | 0x54 | 8 | IntPoint |
| RoughnessTextureSize | 0x5c | 8 | IntPoint |
| AnisotropyTextureSize | 0x64 | 8 | IntPoint |
| SpecularTextureSize | 0x6c | 8 | IntPoint |
| EmissiveTextureSize | 0x74 | 8 | IntPoint |
| OpacityTextureSize | 0x7c | 8 | IntPoint |
| OpacityMaskTextureSize | 0x84 | 8 | IntPoint |
| AmbientOcclusionTextureSize | 0x8c | 8 | IntPoint |
| WetnessMaskTextureSize | 0x94 | 8 | IntPoint |
| PorosityTextureSize | 0x9c | 8 | IntPoint |
| PuddleMaskTextureSize | 0xa4 | 8 | IntPoint |

## MaterialShadingModelField

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ShadingModelField | 0x0 | 2 | RigidBodyErrorCorrection |

## MaterialSpriteElement

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Material | 0x0 | 8 | MaterialInterface |
| DistanceToOpacityCurve | 0x8 | 8 | CurveFloat |
| bSizeIsInScreenSpace | 0x10 | 1 |  |
| BaseSizeX | 0x14 | 4 | MaterialSpriteElement |
| BaseSizeY | 0x18 | 4 | ParameterGroupData |
| DistanceToSizeCurve | 0x20 | 8 | CurveFloat |

## MemberHealthInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CharacterLiveStatus | 0x0 | 4 | MemberHealthInfo |
| Health | 0x4 | 4 | MemberHealthInfo |
| HealthMAX | 0x8 | 4 | MemberHealthInfo |
| BaseHealthMax | 0xc | 4 | MemberHealthInfo |
| ImpendingDeathHealth | 0x10 | 4 | MemberHealthInfo |
| ImpendingDeathHealthMax | 0x14 | 4 | MemberHealthInfo |
| ArmourHealth | 0x18 | 4 | MemberHealthInfo |
| ArmourHealthMax | 0x1c | 4 | MarkingAnimDataInfo |
| HelmetArmourHealth | 0x20 | 4 | MemberHealthInfo |
| HelmetArmourHealthMax | 0x24 | 4 | MemberHealthInfo |
| ShieldHealth | 0x28 | 4 | MemberHealthInfo |
| ShieldHealthMax | 0x2c | 4 | MemberHealthInfo |
| NeedShowRescueNum | 0x30 | 4 | MemberHealthInfo |
| CurrentRescuingProcessEndTimestamp | 0x34 | 4 | MemberHealthInfo |
| ServerRescueStartTime | 0x38 | 4 | MemberHealthInfo |
| ButterRescureState | 0x3c | 4 | MemberHealthInfo |
| ButterRescureStartTime | 0x40 | 4 | MemberHealthInfo |
| ButterRescureEndTime | 0x44 | 4 | MemberHealthInfo |
| RemoteRescureBuffStartTime | 0x48 | 4 | MemberHealthInfo |
| RemoteRescureBuffEndTime | 0x4c | 4 | SceneWeaponInfo |

## MemberReference

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MemberParent | 0x0 | 8 | Object |
| MemberScope | 0x8 | 16 | MemberReference |
| MemberName | 0x18 | 8 | SMGraphProperty_Base |
| MemberGuid | 0x20 | 16 | Guid |
| bSelfContext | 0x30 | 1 |  |
| bWasDeprecated | 0x31 | 1 |  |

## MeshBuildSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bUseMikkTSpace | 0x0 | 1 |  |
| bRecomputeNormals | 0x0 | 1 |  |
| bRecomputeTangents | 0x0 | 1 |  |
| bComputeWeightedNormals | 0x0 | 1 |  |
| bRemoveDegenerates | 0x0 | 1 |  |
| bBuildAdjacencyBuffer | 0x0 | 1 |  |
| bBuildReversedIndexBuffer | 0x0 | 1 |  |
| bUseHighPrecisionTangentBasis | 0x0 | 1 |  |
| bUseFullPrecisionUVs | 0x1 | 1 |  |
| bUseBackwardsCompatibleF16TruncUVs | 0x1 | 1 |  |
| bGenerateLightmapUVs | 0x1 | 1 |  |
| bGenerateDistanceFieldAsIfTwoSided | 0x1 | 1 |  |
| UseNormalizedUVsBitMask | 0x4 | 4 | MeshBuildSettings |
| MinLightmapResolution | 0x8 | 4 | MeshBuildSettings |
| SrcLightmapIndex | 0xc | 4 | MeshBuildSettings |
| DstLightmapIndex | 0x10 | 4 | MeshBuildSettings |
| BuildScale | 0x14 | 4 | MeshBuildSettings |
| BuildScale3D | 0x18 | 12 | Vector |
| DistanceFieldResolutionScale | 0x24 | 4 | MeshBuildSettings |
| DistanceFieldReplacementMesh | 0x28 | 8 | StaticMesh |
| MaxLumenMeshCards | 0x30 | 4 | SkeletalMeshBuildSettings |

## MeshComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OverrideMaterials | 0x5a8 | 16 |  |
| OverrideMaterialSoftPtrArray | 0x5b8 | 16 |  |
| bUseMaterialParameterLerpTrack | 0x6f8 | 1 |  |
| bEnableMaterialParameterCaching | 0x710 | 1 |  |

## MeshDisplacementMap

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Texture | 0x0 | 8 | Texture2D |
| Magnitude | 0x8 | 4 | MeshDisplacementMap |
| Center | 0xc | 4 |  |

## MeshNaniteSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bEnabled | 0x0 | 1 |  |
| bExplicitTangents | 0x0 | 1 |  |
| bLerpUVs | 0x0 | 1 |  |
| bSeparable | 0x0 | 1 |  |
| bVoxelNDF | 0x0 | 1 |  |
| bVoxelOpacity | 0x0 | 1 |  |
| ShapePreservation | 0x1 | 1 | ENaniteShapePreservation |
| PositionPrecision | 0x4 | 4 | MeshNaniteSettings |
| NormalPrecision | 0x8 | 4 | MeshNaniteSettings |
| TangentPrecision | 0xc | 4 | MeshNaniteSettings |
| BoneWeightPrecision | 0x10 | 4 | MeshNaniteSettings |
| TargetMinimumResidencyInKB | 0x14 | 4 | MeshNaniteSettings |
| KeepPercentTriangles | 0x18 | 4 | MeshNaniteSettings |
| TrimRelativeError | 0x1c | 4 | MeshNaniteSettings |
| FallbackTarget | 0x20 | 1 | ENaniteFallbackTarget |
| FallbackPercentTriangles | 0x24 | 4 | MeshNaniteSettings |
| FallbackRelativeError | 0x28 | 4 | MeshNaniteSettings |
| FallbackTargetSourceModelMinLOD | 0x2c | 4 | MeshNaniteSettings |
| FallbackTargetSourceModelNumLOD | 0x30 | 4 | MaterialShadingModelField |
| FoliageOverOcclusionBias | 0x34 | 4 | MeshNaniteSettings |
| MaxEdgeLengthFactor | 0x38 | 4 | MeshNaniteSettings |
| NumRays | 0x3c | 4 | MeshNaniteSettings |
| VoxelLevel | 0x40 | 4 | MeshNaniteSettings |
| RayBackUp | 0x44 | 4 | MeshNaniteSettings |
| DisplacementUVChannel | 0x48 | 4 | MeshDisplacementMap |
| DisplacementMaps | 0x50 | 16 |  |
| NaniteAssemblyData | 0x60 | 32 | NaniteAssemblyData |

## MeshUVChannelInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bInitialized | 0x0 | 1 |  |
| bOverrideDensities | 0x1 | 1 |  |
| LocalUVDensities | 0x4 | 4 | BlueprintComponentDelegateBinding |

## MinimalViewInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x0 | 16 | EncVector |
| Rotation | 0x10 | 12 | Rotator |
| FOV | 0x1c | 4 | RawDistributionVector |
| DesiredFOV | 0x20 | 4 | MinimalViewInfo |
| OrthoWidth | 0x24 | 4 | MinimalViewInfo |
| OrthoNearClipPlane | 0x28 | 4 | MinimalViewInfo |
| OrthoFarClipPlane | 0x2c | 4 | MinimalViewInfo |
| AspectRatio | 0x30 | 4 | MinimalViewInfo |
| bConstrainAspectRatio | 0x34 | 1 |  |
| bUseFieldOfViewForLOD | 0x34 | 1 |  |
| ProjectionMode | 0x35 | 1 | ECameraProjectionMode |
| PostProcessBlendWeight | 0x38 | 4 | PostProcessSettings |
| PostProcessSettings | 0x40 | 2480 | PostProcessSettings |
| OffCenterProjectionOffset | 0x9f0 | 8 | Vector2D |

## MobileDOFConfigs

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FarDistance | 0x0 | 4 | BaseDOFConfig |
| FarDOFConfig | 0x4 | 16 | BaseDOFConfig |
| NearDOFConfig | 0x14 | 16 | BaseDOFConfig |

## ModifierSpec

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EvaluatedMagnitude | 0x0 | 4 | GameplayEffectSpec |

## ModularWeaponDynamicAttrbuites

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CharacterOwnerUin | 0x28 | 8 | AmmoDataItem |
| AmmoContext | 0x30 | 16 | AmmoContext |
| OverHeatContext | 0x40 | 16 | OverHeatContext |

## ModularWeaponDynamicAttributesBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PartGids | 0x8 | 16 |  |
| Attributes | 0x18 | 16 |  |

## ModularWeaponInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| WeaponPartNodes | 0x0 | 16 |  |
| WeaponDynamicAttrs | 0x10 | 80 | ModularWeaponDynamicAttrbuites |
| Perk | 0x60 | 32 | WeaponPerk |
| PoorItemId | 0x80 | 8 | ModularWeaponInfo |
| SkinGid | 0x88 | 8 | ModularWeaponInfo |
| SkinApperanceId | 0x90 | 8 | WeaponSkinInfo |
| SkinInfo | 0x98 | 208 | WeaponSkinInfo |
| bLockApperance | 0x168 | 1 |  |

## ModulatorContinuousParams

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ParameterName | 0x0 | 8 | ModulatorContinuousParams |
| Default | 0x8 | 4 | ModulatorContinuousParams |
| MinInput | 0xc | 4 | ModulatorContinuousParams |
| MaxInput | 0x10 | 4 | ModulatorContinuousParams |
| MinOutput | 0x14 | 4 | ModulatorContinuousParams |
| MaxOutput | 0x18 | 4 | DistanceDatum |
| ParamMode | 0x1c | 1 | ModulationParamMode |

## MotionActionExecuteParam

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Anim | 0x0 | 8 | AnimMontage |
| BasicLocomotionAnim | 0x8 | 8 | AnimSequence |
| AdditiveLocomotionAnim | 0x10 | 8 | AnimSequence |
| bPoseMatching | 0x18 | 1 |  |
| StartFrame | 0x1c | 4 | MotionActionExecuteParam |
| EndFrame | 0x20 | 4 | MotionActionExecuteParam |
| FrameNum | 0x24 | 4 | MotionActionExecuteParam |
| PlayRate | 0x28 | 4 | MotionActionExecuteParam |
| PathPoints | 0x30 | 16 |  |
| StateName | 0x40 | 8 | MotionActionExecuteParam |
| ExtParams | 0x48 | 16 | MotionActionExtParams |
| AnimId | 0x58 | 8 | MotionActionExecuteParam |
| AnimPath | 0x60 | 8 | MotionActionExecuteParam |
| BasicLocomotionAnimID | 0x68 | 8 | MotionActionExecuteParam |
| AdditiveLocomotionAnimID | 0x70 | 8 | MotionRequestConcatPoint |
| AnimSoftPtr | 0x78 | 40 | AnimationAsset |
| BasicLocomotionAnimSoftPtr | 0xa0 | 40 | AnimationAsset |
| AdditiveLocomotionAnimSoftPtr | 0xc8 | 40 | AnimationAsset |

## MotionActionExtParam

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | RootMotionActionInfo |
| Value | 0x8 | 8 | Object |

## MotionActionExtParams

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ParamList | 0x0 | 16 |  |

## MotionActionMsgBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MsgSeq | 0x8 | 4 | MotionActionMsgBase |
| Time | 0xc | 4 | MotionActionMsg_NewActionFrames |

## MotionActionMsg_NewActionFrames

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PreFrameID | 0x0 | 4 | MotionActionMsg_NewActionFrames |
| StartFrameID | 0x4 | 4 | MotionActionMsg_NewActionFrames |
| requestId | 0x8 | 4 | AIRequestID |
| TransitionIndex | 0xc | 4 | MotionActionMsg_NewActionFrames |
| StateName | 0x10 | 8 | MotionActionMsg_NewActionFrames |
| ActionClass | 0x18 | 8 | Class |
| AnimId | 0x20 | 8 | MotionActionMsg_NewActionFrames |
| AnimPlayRate | 0x28 | 4 |  |
| bAnimLoop | 0x2c | 1 |  |
| StartTime | 0x30 | 4 | MotionActionMsg_NewActionFrames |
| FrameTime | 0x34 | 4 | DFMAICharacter |
| bWaitPreActionFinish | 0x38 | 1 |  |
| bNoneMotionFrame | 0x39 | 1 |  |
| AnimFrameSequence | 0x40 | 16 | MotionActionNumberSequence |
| LocXSequence | 0x50 | 16 | MotionActionNumberSequence |
| LocYSequence | 0x60 | 16 | MotionActionNumberSequence |
| LocZSequence | 0x70 | 16 | MotionActionNumberSequence |
| YawSequence | 0x80 | 16 | MotionActionNumberSequence |

## MotionActionMsg_NewTickActionFrame

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PreFrameID | 0x0 | 4 | MotionActionMsg_NewTickActionFrame |
| FrameID | 0x4 | 4 |  |
| requestId | 0x8 | 4 | AIRequestID |
| TransitionIndex | 0xc | 4 | MotionActionMsg_NewTickActionFrame |
| Transition | 0x10 | 304 | MotionStateTransition |
| StartTime | 0x140 | 4 | MotionStateTransitionRequestSyncInfo |
| bWaitPreActionFinish | 0x144 | 1 |  |

## MotionActionNumberSequence

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## MotionAnimState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Anim | 0x0 | 8 | AnimSequenceBase |
| Frame | 0x8 | 4 | MotionActionMsgBase |

## MotionCorrectionActorTarget

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Actor | 0x0 | 8 | Actor |
| offset | 0x8 | 12 | Vector_NetQuantize |

## MotionCorrectionInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Sections | 0x0 | 16 |  |
| SectionTargets | 0x10 | 80 |  |

## MotionCorrectionSection

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SectionStart | 0x0 | 4 | MotionCorrectionSection |
| SectionEnd | 0x4 | 4 | MotionCorrectionSection |
| SectionDuration | 0x8 | 4 | MotionCorrectionSection |
| Target | 0x10 | 80 | MotionCorrectionTarget |
| AnimDisplacementSize | 0x60 | 4 | MotionCorrectionSection |
| AnimRotationSize | 0x64 | 4 | MotionCorrectionSection |
| AnimDisplacementAvgSize | 0x68 | 4 | MotionCorrectionTarget |
| AnimRotationAvgSize | 0x6c | 4 | MotionCorrectionSection |

## MotionCorrectionTarget

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Key | 0x0 | 1 | EMotionCorrectionTargetKey |
| bCorrectLocation | 0x1 | 1 |  |
| TargetWorldLocation | 0x4 | 12 | Vector |
| LocationTargetActor | 0x10 | 24 | MotionCorrectionActorTarget |
| bCorrectOrientation | 0x28 | 1 |  |
| TargetWorldYaw | 0x2c | 4 | AnimRootMotionInfo |
| bFaceLocation | 0x30 | 1 |  |
| FaceLocation | 0x34 | 12 | Vector |
| FaceActor | 0x40 | 8 | Actor |
| bKeepAnimDisplacement | 0x48 | 1 |  |

## MotionPath

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SumDistanceToStart | 0x10 | 16 |  |
| Segments | 0x20 | 16 |  |

## MotionPathParam

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Segment | 0x0 | 4 | MotionPathParam |
| Distance | 0x4 | 4 | MotionPathState |

## MotionPathState

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PathParam | 0x0 | 8 | MotionPathParam |
| Direction | 0x8 | 4 | MotionAnimState |

## MotionRequestConcatPoint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| requestId | 0x0 | 4 | AIRequestID |
| TransitionIndex | 0x4 | 4 | MotionRequestConcatPoint |
| StateName | 0x8 | 8 | MotionRequestConcatPoint |
| bWaitActionFinish | 0x10 | 1 |  |
| bAbortByTime | 0x11 | 1 |  |
| AbortTime | 0x14 | 4 | MotionRequestConcatPoint |
| AbortActionFrame | 0x18 | 4 | MotionPathParam |
| PathState | 0x1c | 12 | MotionPathState |
| AnimState | 0x28 | 16 | MotionAnimState |

## MotionStateTransition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FromState | 0x0 | 8 | MotionStateTransition |
| ToState | 0x8 | 8 | MotionActionExecuteParam |
| ActionClass | 0x10 | 8 | Class |
| ActionParam | 0x18 | 240 | MotionActionExecuteParam |
| AnimList | 0x108 | 16 |  |
| Action | 0x118 | 8 | PathMotionAction |

## MotionStateTransitionRequestSyncInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| requestId | 0x0 | 4 | AIRequestID |
| RequestName | 0x4 | 8 |  |
| Path | 0x10 | 48 | MotionPath |
| ActionSequence | 0x40 | 16 |  |
| bAtomic | 0x50 | 1 |  |

## MovementComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| UpdatedComponent | 0xf8 | 8 | SceneComponent |
| UpdatedPrimitive | 0x100 | 8 | PrimitiveComponent |
| Velocity | 0x10c | 12 | Vector |
| PlaneConstraintNormal | 0x118 | 12 | Vector |
| PlaneConstraintOrigin | 0x124 | 12 | Vector |
| bUpdateOnlyIfRendered | 0x130 | 1 |  |
| bAutoUpdateTickRegistration | 0x130 | 1 |  |
| bTickBeforeOwner | 0x130 | 1 |  |
| bAutoRegisterUpdatedComponent | 0x130 | 1 |  |
| bConstrainToPlane | 0x130 | 1 |  |
| bSnapToPlaneAtStart | 0x130 | 1 |  |
| bAutoRegisterPhysicsVolumeUpdates | 0x130 | 1 |  |
| bComponentShouldUpdatePhysicsVolume | 0x130 | 1 |  |
| PlaneConstraintAxisSetting | 0x133 | 1 | EPlaneConstraintAxisSetting |

## MovementProperties

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bCanCrouch | 0x0 | 1 |  |
| bCanJump | 0x0 | 1 |  |
| bCanWalk | 0x0 | 1 |  |
| bCanSwim | 0x0 | 1 |  |
| bCanFly | 0x0 | 1 |  |

## MultiLegIKData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| IKTargetLocation | 0x0 | 12 | Vector |
| DesiredFoothold | 0xc | 12 | Vector |
| GroundNormal | 0x18 | 12 | Vector |
| bIsAdjusting | 0x24 | 1 |  |
| bGroundTraceHit | 0x25 | 1 |  |
| YawOffset | 0x28 | 4 |  |

## MultiLegSyncItemConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | MultiLegSyncSnapshot |
| Source | 0x8 | 1 | EMultiLegSyncSource |
| bSyncScale | 0x9 | 1 |  |
| SpaceOverride | 0xa | 1 | EMultiLegSyncSpace |
| bEnabled | 0xb | 1 |  |

## MultiLegSyncItemSample

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | MultiLegIKData |
| bValid | 0x8 | 1 |  |
| bHasScale | 0x9 | 1 |  |
| Transform | 0x10 | 48 | Transform |

## MultiLegSyncSnapshot

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Sequence | 0x0 | 4 | MultiLegSyncSnapshot |
| ServerTime | 0x8 | 8 | MultiLegSyncItemSample |
| Items | 0x10 | 16 |  |

## MutexQueueItem

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InfoRow | 0x0 | 32 | MutexRegisterTableRow |
| WidgetInstance | 0x20 | 8 | UserWidget |
| OccupyTimeCount | 0x28 | 4 | MutexQueueItem |
| WaitingTimeCount | 0x2c | 4 |  |

## MutexRegisterTableRow

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| WidgetName | 0x10 | 8 | MutexRegisterTableRow |
| PriorityType | 0x18 | 1 | EWidgetPriorityType |
| bPreemptSamePriority | 0x19 | 1 |  |
| bRecoverAfterPreempted | 0x1a | 1 |  |
| OccupyTimeLimit | 0x1c | 4 | DescRowBase |

## NameCurveKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Time | 0x0 | 4 | NameCurveKey |
| Value | 0x4 | 8 | PurchaseInfo |

## NamedEmitterMaterial

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | GPUMeshLocalVectorFieldInfo |
| Material | 0x8 | 8 | MaterialInterface |

## NaniteAssemblyData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Parts | 0x0 | 16 |  |
| Nodes | 0x10 | 16 |  |

## NavAgentProperties

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AgentRadius | 0x4 | 4 | NavAgentProperties |
| AgentHeight | 0x8 | 4 | NavAgentProperties |
| AgentStepHeight | 0xc | 4 | NavAgentProperties |
| NavWalkingSearchHeightScale | 0x10 | 4 | NameCurveKey |
| PreferredNavData | 0x18 | 24 | SoftClassPath |

## NavAgentSelector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bSupportsAgent0 | 0x0 | 1 |  |
| bSupportsAgent1 | 0x0 | 1 |  |
| bSupportsAgent2 | 0x0 | 1 |  |
| bSupportsAgent3 | 0x0 | 1 |  |
| bSupportsAgent4 | 0x0 | 1 |  |
| bSupportsAgent5 | 0x0 | 1 |  |
| bSupportsAgent6 | 0x0 | 1 |  |
| bSupportsAgent7 | 0x0 | 1 |  |
| bSupportsAgent8 | 0x1 | 1 |  |
| bSupportsAgent9 | 0x1 | 1 |  |
| bSupportsAgent10 | 0x1 | 1 |  |
| bSupportsAgent11 | 0x1 | 1 |  |
| bSupportsAgent12 | 0x1 | 1 |  |
| bSupportsAgent13 | 0x1 | 1 |  |
| bSupportsAgent14 | 0x1 | 1 |  |
| bSupportsAgent15 | 0x1 | 1 |  |

## NavDataConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x30 | 8 | NavAgentProperties |
| Color | 0x38 | 4 | Color |
| DefaultQueryExtent | 0x3c | 12 | Vector |
| NavigationDataClass | 0x48 | 8 | Class |
| NavDataClass | 0x50 | 40 | Class |

## NavMovementComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| NavAgentProps | 0x138 | 48 | NavAgentProperties |
| FixedPathBrakingDistance | 0x168 | 4 | ArchVisCharacter |
| bUpdateNavAgentWithOwnersCollision | 0x16c | 1 |  |
| bUseAccelerationForPaths | 0x16c | 1 |  |
| bUseFixedBrakingDistanceForPaths | 0x16c | 1 |  |
| MovementState | 0x16d | 1 | MovementProperties |
| PathFollowingComp | 0x170 | 8 | Object |

## NavigationLinkBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LeftProjectHeight | 0x0 | 4 | NavigationLinkBase |
| MaxFallDownLength | 0x4 | 4 | NavigationLinkBase |
| ExtData | 0xc | 4 | NavigationLinkBase |
| SnapRadius | 0x10 | 4 | NavigationLinkBase |
| SnapHeight | 0x14 | 4 | NavDataConfig |
| SupportedAgents | 0x18 | 4 | NavAgentSelector |
| bSupportsAgent0 | 0x1c | 1 |  |
| bSupportsAgent1 | 0x1c | 1 |  |
| bSupportsAgent2 | 0x1c | 1 |  |
| bSupportsAgent3 | 0x1c | 1 |  |
| bSupportsAgent4 | 0x1c | 1 |  |
| bSupportsAgent5 | 0x1c | 1 |  |
| bSupportsAgent6 | 0x1c | 1 |  |
| bSupportsAgent7 | 0x1c | 1 |  |
| bSupportsAgent8 | 0x1d | 1 |  |
| bSupportsAgent9 | 0x1d | 1 |  |
| bSupportsAgent10 | 0x1d | 1 |  |
| bSupportsAgent11 | 0x1d | 1 |  |
| bSupportsAgent12 | 0x1d | 1 |  |
| bSupportsAgent13 | 0x1d | 1 |  |
| bSupportsAgent14 | 0x1d | 1 |  |
| bSupportsAgent15 | 0x1d | 1 |  |
| Direction | 0x20 | 1 | ENavLinkDirection |
| bUseSnapHeight | 0x21 | 1 |  |
| bSnapToCheapestArea | 0x21 | 1 |  |
| bCustomFlag0 | 0x21 | 1 |  |
| bCustomFlag1 | 0x21 | 1 |  |
| bCustomFlag2 | 0x21 | 1 |  |
| bCustomFlag3 | 0x21 | 1 |  |
| bCustomFlag4 | 0x21 | 1 |  |
| bCustomFlag5 | 0x21 | 1 |  |
| bCustomFlag6 | 0x22 | 1 |  |
| bCustomFlag7 | 0x22 | 1 |  |
| AreaClass | 0x28 | 8 | Class |

## NetDriverDefinition

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DefName | 0x0 | 8 | NetDriverDefinition |
| DriverClassName | 0x8 | 8 | NetDriverDefinition |
| DriverClassNameFallback | 0x10 | 8 | WorldContext |

## NetworkCosmeticData_Server_Character_OnFire

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FireInfo | 0x8 | 120 | WeaponFireMulticastInfo |
| PlayerViewInfo | 0xd8 | 4 | CharacterMoveHandle |
| CameraViewRotVec | 0xdc | 12 | Vector |
| CameraViewLoc | 0xe8 | 12 | Vector |

## NetworkEmulationProfileDescription

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ProfileName | 0x0 | 16 | NetworkEmulationProfileDescription |
| ToolTip | 0x10 | 16 | PacketSimulationSettings |

## Node

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | Node |
| ParentName | 0x8 | 8 | Node |
| Transform | 0x10 | 48 | Transform |
| DisplayName | 0x40 | 16 | TransformBase |
| bAdvanced | 0x50 | 1 |  |

## NodeItem

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ParentName | 0x0 | 8 | NetworkEmulationProfileDescription |
| Transform | 0x10 | 48 | Transform |

## Object

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## OrientedBox

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Center | 0x0 | 12 | Vector |
| AxisX | 0xc | 12 | Vector |
| AxisY | 0x18 | 12 | Vector |
| AxisZ | 0x24 | 12 | Vector |
| ExtentX | 0x30 | 4 | OrientedBox |
| ExtentY | 0x34 | 4 | OrientedBox |
| ExtentZ | 0x38 | 4 | EncBoxSphereBounds |

## OverHeatContext

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TotalHeat | 0x0 | 4 | OverHeatContext |
| OverHeatSecondsLeft | 0x4 | 4 | OverHeatContext |
| HeatDecreasePerSecond | 0x8 | 4 |  |

## PACharacterPhysicalAnimationBoneSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bEnabled | 0x0 | 1 |  |
| Bones | 0x8 | 16 |  |
| PhysicalAnimationData | 0x18 | 36 | PhysicalAnimationData |
| BonesBelowPhysicsWeight | 0x3c | 4 | PACharacterPhysicalAnimationConfig |

## PACharacterPhysicalAnimationConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BonePhysicalAnimationSettings | 0x0 | 16 |  |
| OverrideStrengthMultiplyer | 0x10 | 4 | MultiLegSyncItemConfig |

## POV

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x0 | 12 | Vector |
| Rotation | 0xc | 12 | Rotator |
| FOV | 0x18 | 4 | MeshBuildSettings |

## POVFloatSetting

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Option | 0x0 | 1 | EPOVModifyOption |
| Value | 0x4 | 4 | MobileDOFConfigs |

## PackedRGB10A2N

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Packed | 0x0 | 4 | Quat |

## PackedRGBA16N

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| XY | 0x0 | 4 | PackedRGBA16N |
| ZW | 0x4 | 4 | PackedRGB10A2N |

## PacketSimulationSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PktLoss | 0x0 | 4 | PacketSimulationSettings |
| PktJitter | 0x4 | 4 | PacketSimulationSettings |
| PktLossMaxSize | 0x8 | 4 | PacketSimulationSettings |
| PktLossMinSize | 0xc | 4 | PacketSimulationSettings |
| PktOrder | 0x10 | 4 | PacketSimulationSettings |
| PktDup | 0x14 | 4 | PacketSimulationSettings |
| PktLag | 0x18 | 4 | PacketSimulationSettings |
| PktLagVariance | 0x1c | 4 | PacketSimulationSettings |
| PktLagMin | 0x20 | 4 | PacketSimulationSettings |
| PktLagMax | 0x24 | 4 | PacketSimulationSettings |
| PktIncomingLagMin | 0x28 | 4 | PacketSimulationSettings |
| PktIncomingLagMax | 0x2c | 4 | PacketSimulationSettings |
| PktIncomingLoss | 0x30 | 4 | PacketSimulationSettings |
| PktIncomingJitter | 0x34 | 4 | ChannelDefinition |

## ParamSplinePointParameter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| width | 0x0 | 4 | ParamSplinePointParameter |
| Depth | 0x4 | 4 | ParamSplinePointParameter |
| WidthFalloff | 0x8 | 4 |  |
| CustomProperties | 0x10 | 80 |  |

## ParameterChannelNames

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| R | 0x0 | 24 | ParameterChannelNames |
| G | 0x18 | 24 | ParameterChannelNames |
| B | 0x30 | 24 | ParameterChannelNames |
| A | 0x48 | 24 | MaterialSpriteElement |

## ParameterGroupData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GroupName | 0x0 | 16 |  |
| GroupSortPriority | 0x10 | 4 | ClientReceiveData |

## PassiveSoundMixModifier

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SoundMix | 0x0 | 8 | SoundMix |
| MinVolumeThreshold | 0x8 | 4 | PassiveSoundMixModifier |
| MaxVolumeThreshold | 0xc | 4 | SoundAttenuationSettings |

## PatchMatchRule

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Rule | 0x0 | 1 | EMatchRule |
| Operator | 0x1 | 1 | EMatchOperator |
| size | 0x4 | 4 |  |
| Formaters | 0x8 | 16 |  |

## Pawn

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bUseControllerRotationPitch | 0x378 | 1 |  |
| bUseControllerRotationYaw | 0x378 | 1 |  |
| bUseControllerRotationRoll | 0x378 | 1 |  |
| bCanAffectNavigationGeneration | 0x378 | 1 |  |
| BaseEyeHeight | 0x37c | 4 |  |
| AutoPossessPlayer | 0x380 | 1 | EAutoReceiveInput |
| AutoPossessAI | 0x381 | 1 | EAutoPossessAI |
| RemoteViewPitch | 0x382 | 1 |  |
| AIControllerClass | 0x388 | 8 | Class |
| PlayerState | 0x390 | 8 | PlayerState |
| LastHitBy | 0x3a0 | 8 | Controller |
| Controller | 0x3a8 | 8 | Controller |
| ControlInputVector | 0x3b4 | 12 | Vector |
| LastControlInputVector | 0x3c0 | 12 | Vector |

## PawnMovementComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PawnOwner | 0x178 | 8 | Pawn |

## PendantApperanceInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ShowType | 0x0 | 1 | EMysticalPendantShowType |
| Rarity | 0x4 | 4 | KillInfo |
| PendantMysticalId | 0x8 | 8 | PendantApperanceInfo |
| PendantMaterialRandomSeed | 0x10 | 8 |  |
| PendantMaterialParams | 0x18 | 16 |  |

## PendantInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PendantId | 0x0 | 8 | PendantInfo |
| PendantGUID | 0x8 | 8 | PendantInfo |
| UniqueNumber | 0x10 | 8 | PendantInfo |
| CustomName | 0x18 | 16 | PendantApperanceInfo |
| SuitActive | 0x28 | 1 |  |
| ApperanceInfos | 0x30 | 16 |  |

## PerBoneInterpolation

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BoneReference | 0x0 | 16 | BoneReference |
| InterpolationSpeedPerSec | 0x10 | 4 | BlendProfileBoneEntry |

## PerPlatformBool

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Default | 0x0 | 1 |  |

## PerPlatformInt

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Default | 0x0 | 4 | LandscapeLayer |

## PerPlatformString

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Default | 0x0 | 16 | NamedEmitterMaterial |

## PhysicalAnimationData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BodyName | 0x0 | 8 | PhysicalAnimationData |
| bIsLocalSimulation | 0x8 | 1 |  |
| OrientationStrength | 0xc | 4 | PhysicalAnimationData |
| AngularVelocityStrength | 0x10 | 4 | PhysicalAnimationData |
| PositionStrength | 0x14 | 4 | PhysicalAnimationData |
| VelocityStrength | 0x18 | 4 | PhysicalAnimationData |
| MaxLinearForce | 0x1c | 4 | PhysicalAnimationData |
| MaxAngularForce | 0x20 | 4 | PACharacterPhysicalAnimationBoneSettings |

## PhysicalAnimationProfile

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ProfileName | 0x0 | 8 | TireFrictionScalePair |
| PhysicalAnimationData | 0x8 | 36 | PhysicalAnimationData |

## PhysicalCameraConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DepthOfFieldFocalDistance | 0x0 | 4 | PhysicalCameraConfig |
| DepthOfFieldSensorWidth | 0x4 | 4 | PhysicalCameraConfig |
| DepthOfFieldFstop | 0x8 | 4 | PhysicalCameraConfig |
| DepthOfFieldMinFstop | 0xc | 4 | PhysicalCameraConfig |
| DepthOfFieldBladeCount | 0x10 | 4 | CameraXppChangeConfig |

## PhysicalSurfaceName

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Type | 0x0 | 1 | EPhysicalSurface |
| Name | 0x4 | 8 | PhysicsConstraintProfileHandle |

## PhysicsConstraintProfileHandle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ProfileProperties | 0x0 | 260 | ConstraintProfileProperties |
| ProfileName | 0x104 | 8 | PhysicalAnimationProfile |

## Plane

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| W | 0xc | 4 | Vector2D |

## PlanningTransitionInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MotionType | 0x0 | 4 | PlanningTransitionInfo |
| MustMotion | 0x4 | 1 |  |
| NeedPlanning | 0x8 | 4 | PlanningTransitionInfo |
| PlanningFrameNumber | 0xc | 4 | PlanningTransitionInfo |
| PlanningSpeed | 0x10 | 4 | DebugTransitionInfo |
| StartPos | 0x14 | 12 | Vector |
| EndPos | 0x20 | 12 | Vector |
| StartRot | 0x2c | 12 | Rotator |
| EndRot | 0x38 | 12 | Rotator |
| PlanningPath | 0x48 | 16 |  |
| AllPath | 0x58 | 16 |  |

## PlatformInterfaceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DataName | 0x0 | 8 | PlatformInterfaceData |
| Type | 0x8 | 1 | EPlatformInterfaceDataType |
| IntValue | 0xc | 4 |  |
| FloatValue | 0x10 | 4 | PlatformInterfaceData |
| StringValue | 0x18 | 16 |  |
| ObjectValue | 0x28 | 8 | Object |

## PlayerCameraManager

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PCOwner | 0x370 | 8 | PlayerController |
| TransformComponent | 0x378 | 8 | SceneComponent |
| DefaultFOV | 0x388 | 4 | PlayerCameraManager |
| DefaultOrthoWidth | 0x390 | 4 | PlayerCameraManager |
| DefaultAspectRatio | 0x398 | 4 | PlayerCameraManager |
| CameraCache | 0x3e0 | 2640 | CameraCacheEntry |
| LastFrameCameraCache | 0xe30 | 2640 | CameraCacheEntry |
| ViewTarget | 0x1880 | 2656 | TViewTarget |
| PendingViewTarget | 0x22e0 | 2656 | TViewTarget |
| CameraCachePrivate | 0x2d60 | 2640 | CameraCacheEntry |
| LastFrameCameraCachePrivate | 0x37b0 | 2640 | CameraCacheEntry |
| ModifierList | 0x4200 | 16 |  |
| DefaultModifiers | 0x4210 | 16 |  |
| FreeCamDistance | 0x4220 | 4 | GPSequenceNetSyncActor |
| FreeCamOffset | 0x4224 | 12 | Vector |
| ViewTargetOffset | 0x4230 | 12 | Vector |
| CameraLensEffects | 0x4250 | 16 |  |
| CachedCameraShakeMod | 0x4260 | 8 | CameraModifier_CameraShake |
| AnimInstPool | 0x4268 | 8 | CameraAnimInst |
| PostProcessBlendCache | 0x42a8 | 16 |  |
| ActiveAnims | 0x42c8 | 16 |  |
| FreeAnims | 0x42d8 | 16 |  |
| AnimCameraActor | 0x42e8 | 8 | CameraActor |
| bIsOrthographic | 0x42f0 | 1 |  |
| bDefaultConstrainAspectRatio | 0x42f0 | 1 |  |
| bClientSimulatingViewTarget | 0x42f0 | 1 |  |
| bUseClientSideCameraUpdates | 0x42f0 | 1 |  |
| bGameCameraCutThisFrame | 0x42f1 | 1 |  |
| ViewPitchMin | 0x42f4 | 4 | PlayerCameraManager |
| ViewPitchMax | 0x42f8 | 4 | PlayerCameraManager |
| ViewYawMin | 0x42fc | 4 | PlayerCameraManager |
| ViewYawMax | 0x4300 | 4 | PlayerCameraManager |
| ViewRollMin | 0x4304 | 4 | PlayerCameraManager |
| ViewRollMax | 0x4308 | 4 | PlayerCameraManager |
| ServerUpdateCameraTimeout | 0x4310 | 4 |  |

## PlayerController

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Player | 0x3e8 | 8 | Player |
| AcknowledgedPawn | 0x3f0 | 8 | Pawn |
| ControllingDirTrackInst | 0x3f8 | 8 | InterpTrackInstDirector |
| MyHUD | 0x400 | 8 | HUD |
| PlayerCameraManager | 0x408 | 8 | PlayerCameraManager |
| PlayerCameraManagerClass | 0x410 | 8 | Class |
| bAutoManageActiveCameraTarget | 0x418 | 1 |  |
| TargetViewRotation | 0x41c | 12 | Rotator |
| SmoothTargetViewRotationSpeed | 0x434 | 4 | PlayerController |
| HiddenActors | 0x440 | 16 |  |
| HiddenPrimitiveComponents | 0x450 | 16 |  |
| LastSpectatorStateSynchTime | 0x464 | 4 | PlayerController |
| LastSpectatorSyncLocation | 0x468 | 12 | Vector |
| LastSpectatorSyncRotation | 0x474 | 12 | Rotator |
| ClientCap | 0x480 | 4 | PlayerController |
| CheatManager | 0x488 | 8 | CheatManager |
| CheatClass | 0x490 | 8 | Class |
| PlayerInput | 0x498 | 8 | PlayerInput |
| ActiveForceFeedbackEffects | 0x4a0 | 16 |  |
| bPlayerIsWaiting | 0x520 | 1 |  |
| NetPlayerIndex | 0x521 | 1 |  |
| PendingSwapConnection | 0x560 | 8 | NetConnection |
| NetConnection | 0x568 | 8 | NetConnection |
| InputYawScale | 0x57c | 4 | PlayerController |
| InputPitchScale | 0x580 | 4 | PlayerController |
| InputRollScale | 0x584 | 4 | PlayerController |
| bShowMouseCursor | 0x588 | 1 |  |
| bEnableClickEvents | 0x588 | 1 |  |
| bEnableTouchEvents | 0x588 | 1 |  |
| bEnableMouseOverEvents | 0x588 | 1 |  |
| bEnableTouchOverEvents | 0x588 | 1 |  |
| bForceFeedbackEnabled | 0x588 | 1 |  |
| ForceFeedbackScale | 0x58c | 4 | PlayerController |
| ClickEventKeys | 0x590 | 16 |  |
| DefaultMouseCursor | 0x5a0 | 1 | EMouseCursor |
| CurrentMouseCursor | 0x5a1 | 1 | EMouseCursor |
| DefaultClickTraceChannel | 0x5a2 | 1 | ECollisionChannel |
| CurrentClickTraceChannel | 0x5a3 | 1 | ECollisionChannel |
| HitResultTraceDistance | 0x5a4 | 4 | PlayerController |
| SeamlessTravelCount | 0x5a8 | 2 | PlayerController |
| LastCompletedSeamlessTravelCount | 0x5aa | 2 |  |
| InactiveStateInputComponent | 0x620 | 8 | InputComponent |
| bShouldPerformFullTickWhenPaused | 0x628 | 1 |  |
| CurrentTouchInterface | 0x640 | 8 | TouchInterface |
| SpectatorPawn | 0x698 | 8 | SpectatorPawn |
| bIsLocalPlayerController | 0x6a4 | 1 |  |
| SpawnLocation | 0x6a8 | 12 | Vector |

## PluginRedirect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OldPluginName | 0x0 | 16 | PluginRedirect |
| NewPluginName | 0x10 | 16 | EdGraphSchemaAction |

## PointerToUberGraphFrame

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## PolyglotTextData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Category | 0x0 | 1 | ELocalizedTextSourceCategory |
| NativeCulture | 0x8 | 16 | PolyglotTextData |
| Namespace | 0x18 | 16 | PolyglotTextData |
| Key | 0x28 | 16 | PolyglotTextData |
| NativeString | 0x38 | 16 |  |
| LocalizedStrings | 0x48 | 80 |  |
| bIsMinimalPatch | 0x98 | 1 |  |
| CachedText | 0xa0 | 24 | Int32Interval |

## PoseTransitionTime

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StandToProneTransitionTime | 0x0 | 4 | PoseTransitionTime |
| StandToCrouchTransitionTime | 0x4 | 4 | PoseTransitionTime |
| CrouchToStandTransitionTime | 0x8 | 4 | PoseTransitionTime |
| CrouchToProneTransitionTime | 0xc | 4 | PoseTransitionTime |
| ProneToStandTransitionTime | 0x10 | 4 | PoseTransitionTime |
| ProneToCrouchTransitionTime | 0x14 | 4 | GPCharacter |

## PostProcessBlurEffectSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GaussianSum | 0x0 | 4 | GaussianBlurEffectSettings |
| PPBlurMethod | 0x4 | 1 | EPPBlurMethod |

## PostProcessSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bOverride_WhiteTemp | 0x0 | 1 |  |
| bOverride_WhiteTint | 0x0 | 1 |  |
| bOverride_ColorSaturation | 0x0 | 1 |  |
| bOverride_ColorContrast | 0x0 | 1 |  |
| bOverride_ColorGamma | 0x0 | 1 |  |
| bOverride_ColorGain | 0x0 | 1 |  |
| bOverride_ColorOffset | 0x0 | 1 |  |
| bOverride_ColorSaturationShadows | 0x0 | 1 |  |
| bOverride_ColorContrastShadows | 0x1 | 1 |  |
| bOverride_ColorGammaShadows | 0x1 | 1 |  |
| bOverride_ColorGainShadows | 0x1 | 1 |  |
| bOverride_ColorOffsetShadows | 0x1 | 1 |  |
| bOverride_ColorSaturationMidtones | 0x1 | 1 |  |
| bOverride_ColorContrastMidtones | 0x1 | 1 |  |
| bOverride_ColorGammaMidtones | 0x1 | 1 |  |
| bOverride_ColorGainMidtones | 0x1 | 1 |  |
| bOverride_ColorOffsetMidtones | 0x2 | 1 |  |
| bOverride_ColorSaturationHighlights | 0x2 | 1 |  |
| bOverride_ColorContrastHighlights | 0x2 | 1 |  |
| bOverride_ColorGammaHighlights | 0x2 | 1 |  |
| bOverride_ColorGainHighlights | 0x2 | 1 |  |
| bOverride_ColorOffsetHighlights | 0x2 | 1 |  |
| bOverride_ColorCorrectionShadowsMax | 0x2 | 1 |  |
| bOverride_ColorCorrectionHighlightsMin | 0x2 | 1 |  |
| bOverride_BlueCorrection | 0x3 | 1 |  |
| bOverride_DarknessCorrection | 0x3 | 1 |  |
| bOverride_ExpandGamut | 0x3 | 1 |  |
| bOverride_FilmWhitePoint | 0x3 | 1 |  |
| bOverride_FilmSaturation | 0x3 | 1 |  |
| bOverride_FilmChannelMixerRed | 0x3 | 1 |  |
| bOverride_FilmChannelMixerGreen | 0x3 | 1 |  |
| bOverride_FilmChannelMixerBlue | 0x3 | 1 |  |
| bOverride_FilmContrast | 0x4 | 1 |  |
| bOverride_FilmDynamicRange | 0x4 | 1 |  |
| bOverride_FilmHealAmount | 0x4 | 1 |  |
| bOverride_FilmToeAmount | 0x4 | 1 |  |
| bOverride_FilmShadowTint | 0x4 | 1 |  |
| bOverride_FilmShadowTintBlend | 0x4 | 1 |  |
| bOverride_FilmShadowTintAmount | 0x4 | 1 |  |
| bOverride_FilmSlope | 0x4 | 1 |  |
| bOverride_FilmToe | 0x5 | 1 |  |
| bOverride_FilmShoulder | 0x5 | 1 |  |
| bOverride_FilmBlackClip | 0x5 | 1 |  |
| bOverride_FilmWhiteClip | 0x5 | 1 |  |
| bOverride_Mobile_ACES_A | 0x5 | 1 |  |
| bOverride_Mobile_ACES_B | 0x5 | 1 |  |
| bOverride_Mobile_ACES_C | 0x5 | 1 |  |
| bOverride_Mobile_ACES_D | 0x5 | 1 |  |
| bOverride_Mobile_ACES_E | 0x6 | 1 |  |
| bOverride_Mobile_LDR_ACES_A | 0x6 | 1 |  |
| bOverride_Mobile_LDR_ACES_B | 0x6 | 1 |  |
| bOverride_Mobile_LDR_ACES_C | 0x6 | 1 |  |
| bOverride_Mobile_LDR_ACES_D | 0x6 | 1 |  |
| bOverride_Mobile_LDR_ACES_E | 0x6 | 1 |  |
| bOverride_Mobile_CG_Exposure | 0x6 | 1 |  |
| bOverride_Mobile_CG_HdrScale | 0x6 | 1 |  |
| bOverride_Mobile_CG_MasterSaturation | 0x7 | 1 |  |
| bOverride_Mobile_CG_MasterTint | 0x7 | 1 |  |
| bOverride_Mobile_CG_Saturation_K0 | 0x7 | 1 |  |
| bOverride_Mobile_CG_Exposure_K0 | 0x7 | 1 |  |
| bOverride_Mobile_CG_Tint_K0 | 0x7 | 1 |  |
| bOverride_Mobile_CG_Saturation_K1 | 0x7 | 1 |  |
| bOverride_Mobile_CG_Exposure_K1 | 0x7 | 1 |  |
| bOverride_Mobile_CG_Tint_K1 | 0x7 | 1 |  |
| bOverride_Mobile_CG_Saturation_K2 | 0x8 | 1 |  |
| bOverride_Mobile_CG_Exposure_K2 | 0x8 | 1 |  |
| bOverride_Mobile_CG_Tint_K2 | 0x8 | 1 |  |
| bOverride_MobileColorGradingLUT | 0x8 | 1 |  |
| bOverride_MobileColorGradingLUTWeight | 0x8 | 1 |  |
| bOverride_SceneColorTint | 0x8 | 1 |  |
| bOverride_SceneFringeIntensity | 0x8 | 1 |  |
| bOverride_ChromaticAberrationStartOffset | 0x8 | 1 |  |
| bOverride_ChromaticAberrationSCaleR | 0x9 | 1 |  |
| bOverride_ChromaticAberrationSCaleG | 0x9 | 1 |  |
| bOverride_AmbientCubemapTint | 0x9 | 1 |  |
| bOverride_AmbientCubemapIntensity | 0x9 | 1 |  |
| bOverride_BloomMethod | 0x9 | 1 |  |
| bOverride_PPBlurMethod | 0x9 | 1 |  |
| bOverride_PPEdgeDetectMethod | 0x9 | 1 |  |
| bOverride_BloomIntensity | 0x9 | 1 |  |
| bOverride_BloomMaxLuminance | 0xa | 1 |  |
| bOverride_BloomMaxLuminanceWithoutExposure | 0xa | 1 |  |
| bOverride_BloomMaxLuminanceWithoutExposureEnabled | 0xa | 1 |  |
| bOverride_MobileBloomMaxLuminance | 0xa | 1 |  |
| bOverride_MobileBloomMaxLuminanceWithoutExposure | 0xa | 1 |  |
| bOverride_BloomThreshold | 0xa | 1 |  |
| bOverride_Bloom1Tint | 0xa | 1 |  |
| bOverride_Bloom1Size | 0xa | 1 |  |
| bOverride_Bloom2Size | 0xb | 1 |  |
| bOverride_Bloom2Tint | 0xb | 1 |  |
| bOverride_Bloom3Tint | 0xb | 1 |  |
| bOverride_Bloom3Size | 0xb | 1 |  |
| bOverride_Bloom4Tint | 0xb | 1 |  |
| bOverride_Bloom4Size | 0xb | 1 |  |
| bOverride_Bloom5Tint | 0xb | 1 |  |
| bOverride_Bloom5Size | 0xb | 1 |  |
| bOverride_Bloom6Tint | 0xc | 1 |  |
| bOverride_Bloom6Size | 0xc | 1 |  |
| bOverride_BloomSizeScale | 0xc | 1 |  |
| bOverride_MobileBloomTint | 0xc | 1 |  |
| bOverride_MobileBloomThreshold | 0xc | 1 |  |
| bOverride_BloomConvolutionTexture | 0xc | 1 |  |
| bOverride_BloomConvolutionSize | 0xc | 1 |  |
| bOverride_BloomConvolutionCenterUV | 0xc | 1 |  |
| bOverride_BloomConvolutionPreFilter | 0xd | 1 |  |
| bOverride_BloomConvolutionPreFilterMin | 0xd | 1 |  |
| bOverride_BloomConvolutionPreFilterMax | 0xd | 1 |  |
| bOverride_BloomConvolutionPreFilterMult | 0xd | 1 |  |
| bOverride_BloomConvolutionBufferScale | 0xd | 1 |  |
| bOverride_BloomDirtMaskIntensity | 0xd | 1 |  |
| bOverride_BloomDirtMaskTint | 0xd | 1 |  |
| bOverride_BloomDirtMask | 0xd | 1 |  |
| bOverride_CameraShutterSpeed | 0xe | 1 |  |
| bOverride_CameraISO | 0xe | 1 |  |
| bOverride_AutoExposureMethod | 0xe | 1 |  |
| bOverride_AutoExposureLowPercent | 0xe | 1 |  |
| bOverride_AutoExposureHighPercent | 0xe | 1 |  |
| bOverride_AutoExposureMinBrightness | 0xe | 1 |  |
| bOverride_AutoExposureMaxBrightness | 0xe | 1 |  |
| bOverride_AutoExposureCalibrationConstant | 0xe | 1 |  |
| bOverride_AutoExposureSpeedUp | 0xf | 1 |  |
| bOverride_AutoExposureSpeedDown | 0xf | 1 |  |
| bOverride_AutoExposureBias | 0xf | 1 |  |
| bOverride_AutoExposureBiasCurve | 0xf | 1 |  |
| bOverride_AutoExposureMeterMask | 0xf | 1 |  |
| bOverride_AutoExposureApplyPhysicalCameraExposure | 0xf | 1 |  |
| bOverride_HistogramLogMin | 0xf | 1 |  |
| bOverride_HistogramLogMax | 0xf | 1 |  |
| bOverride_LocalExposureHighlightContrastScale | 0x10 | 1 |  |
| bOverride_LocalExposureShadowContrastScale | 0x10 | 1 |  |
| bOverride_LocalExposureHighlightContrastCurve | 0x10 | 1 |  |
| bOverride_LocalExposureShadowContrastCurve | 0x10 | 1 |  |
| bOverride_LocalExposureHighlightThreshold | 0x10 | 1 |  |
| bOverride_LocalExposureShadowThreshold | 0x10 | 1 |  |
| bOverride_LocalExposureDetailStrength | 0x10 | 1 |  |
| bOverride_LocalExposureBlurredLuminanceBlend | 0x10 | 1 |  |
| bOverride_LocalExposureBlurredLuminanceKernelSizePercent | 0x11 | 1 |  |
| bOverride_LocalExposureMiddleGreyBias | 0x11 | 1 |  |
| bOverride_MiddleGreyBiasCompensation | 0x11 | 1 |  |
| bOverride_LensFlareMethod | 0x11 | 1 |  |
| bOverride_LensFlareIntensity | 0x11 | 1 |  |
| bOverride_LensFlareTint | 0x11 | 1 |  |
| bOverride_LensFlareBokehSize | 0x11 | 1 |  |
| bOverride_LensFlareThreshold | 0x11 | 1 |  |
| bOverride_LensFlareBokehShape | 0x12 | 1 |  |
| bOverride_LensFlareLineWidth | 0x12 | 1 |  |
| bOverride_LensFlareLineLength | 0x12 | 1 |  |
| bOverride_LensFlareLineIntensity | 0x12 | 1 |  |
| bOverride_LensFlareLineTint | 0x12 | 1 |  |
| bOverride_LensFlareHalo | 0x12 | 1 |  |
| bOverride_LensFlareHaloScaleMin | 0x12 | 1 |  |
| bOverride_LensFlareHaloScaleMax | 0x12 | 1 |  |
| bOverride_LensFlareTints | 0x13 | 1 |  |
| bOverride_LensFlareLocation | 0x13 | 1 |  |
| bOverride_LensFlareTints | 0x13 | 1 |  |
| bOverride_LensFlareLocation | 0x13 | 1 |  |
| bOverride_LensFlareTints | 0x13 | 1 |  |
| bOverride_LensFlareLocation | 0x13 | 1 |  |
| bOverride_LensFlareTints | 0x13 | 1 |  |
| bOverride_LensFlareLocation | 0x13 | 1 |  |
| bOverride_LensFlareTints | 0x14 | 1 |  |
| bOverride_LensFlareLocation | 0x14 | 1 |  |
| bOverride_LensFlareTints | 0x14 | 1 |  |
| bOverride_LensFlareTints | 0x14 | 1 |  |
| bOverride_LensFlareTints | 0x14 | 1 |  |
| bOverride_bUseMobileLensFlare | 0x14 | 1 |  |
| bOverride_MobileLensFlareIntensity | 0x14 | 1 |  |
| bOverride_MobileLensFlareTint | 0x14 | 1 |  |
| bOverride_MobileLensFlareBokehSize | 0x15 | 1 |  |
| bOverride_LensFlareRandomSeed | 0x15 | 1 |  |
| bOverride_LensFlareFlareCount | 0x15 | 1 |  |
| bOverride_LensFlareMinPositionScale | 0x15 | 1 |  |
| bOverride_LensFlareMaxPositionScale | 0x15 | 1 |  |
| bOverride_MobileLensFlareBokehShape | 0x15 | 1 |  |
| bOverride_LensFlareIntensity2 | 0x15 | 1 |  |
| bOverride_LensFlareTint2 | 0x15 | 1 |  |
| bOverride_LensFlareBokehSize2 | 0x16 | 1 |  |
| bOverride_LensFlareRandomSeed2 | 0x16 | 1 |  |
| bOverride_LensFlareFlareCount2 | 0x16 | 1 |  |
| bOverride_LensFlareMinPositionScale2 | 0x16 | 1 |  |
| bOverride_LensFlareMaxPositionScale2 | 0x16 | 1 |  |
| bOverride_LensFlareBokehShape2 | 0x16 | 1 |  |
| bOverride_LensFlareRayTint | 0x16 | 1 |  |
| bOverride_LensFlareRaySliceCount | 0x16 | 1 |  |
| bOverride_LensFlareRayThreshold | 0x17 | 1 |  |
| bOverride_LensFlareRayRandomSeed | 0x17 | 1 |  |
| bOverride_LensFlareRaySize | 0x17 | 1 |  |
| bOverride_LensFlareRayWidth | 0x17 | 1 |  |
| bOverride_LensFlareRayIntensity | 0x17 | 1 |  |
| bOverride_DynamicGlobalIlluminationMethod | 0x17 | 1 |  |
| bOverride_ReflectionMethod | 0x17 | 1 |  |
| bOverride_LumenReflectionQuality | 0x17 | 1 |  |
| bOverride_LumenSceneLightingQuality | 0x18 | 1 |  |
| bOverride_LumenSceneDetail | 0x18 | 1 |  |
| bOverride_LumenSceneViewDistance | 0x18 | 1 |  |
| bOverride_LumenSceneLightingUpdateSpeed | 0x18 | 1 |  |
| bOverride_LumenFinalGatherQuality | 0x18 | 1 |  |
| bOverride_LumenFinalGatherLightingUpdateSpeed | 0x18 | 1 |  |
| bOverride_LumenSSRTAOStepSize | 0x18 | 1 |  |
| bOverride_LumenSSRTAOFoliageStepSize | 0x18 | 1 |  |
| bOverride_LumenSSRTAONoiseStep | 0x19 | 1 |  |
| bOverride_LumenSSRTAOBentNormalThreshold | 0x19 | 1 |  |
| bOverride_LumenSSRTAOThreshold | 0x19 | 1 |  |
| bOverride_LumenSSRTAOTwoSidedFoliageThreshold | 0x19 | 1 |  |
| bOverride_LumenFinalGatherScreenTraces | 0x19 | 1 |  |
| bOverride_LumenMaxTraceDistance | 0x19 | 1 |  |
| bOverride_LumenDiffuseColorBoost | 0x19 | 1 |  |
| bOverride_LumenSkylightLeaking | 0x19 | 1 |  |
| bOverride_LumenFullSkylightLeakingDistance | 0x1a | 1 |  |
| bOverride_LumenRayLightingMode | 0x1a | 1 |  |
| bOverride_LumenReflectionsScreenTraces | 0x1a | 1 |  |
| bOverride_LumenFrontLayerTranslucencyReflections | 0x1a | 1 |  |
| bOverride_LumenMaxRoughnessToTraceReflections | 0x1a | 1 |  |
| bOverride_LumenMaxReflectionBounces | 0x1a | 1 |  |
| bOverride_LumenMaxRefractionBounces | 0x1a | 1 |  |
| bOverride_LumenSurfaceCacheResolution | 0x1a | 1 |  |
| bOverride_VignetteIntensity | 0x1b | 1 |  |
| bOverride_GrainIntensity | 0x1b | 1 |  |
| bOverride_GrainJitter | 0x1b | 1 |  |
| bOverride_AmbientOcclusionIntensity | 0x1b | 1 |  |
| bOverride_AmbientOcclusionStaticFraction | 0x1b | 1 |  |
| bOverride_AmbientOcclusionRadius | 0x1b | 1 |  |
| bOverride_AmbientOcclusionFadeDistance | 0x1b | 1 |  |
| bOverride_AmbientOcclusionFadeRadius | 0x1b | 1 |  |
| bOverride_AmbientOcclusionDistance | 0x1c | 1 |  |
| bOverride_AmbientOcclusionRadiusInWS | 0x1c | 1 |  |
| bOverride_AmbientOcclusionPower | 0x1c | 1 |  |
| bOverride_AmbientOcclusionBias | 0x1c | 1 |  |
| bOverride_AmbientOcclusionQuality | 0x1c | 1 |  |
| bOverride_AmbientOcclusionMipBlend | 0x1c | 1 |  |
| bOverride_AmbientOcclusionMipScale | 0x1c | 1 |  |
| bOverride_AmbientOcclusionMipThreshold | 0x1c | 1 |  |
| bOverride_AmbientOcclusionTemporalBlendWeight | 0x1d | 1 |  |
| bOverride_SSRTAOThreshold | 0x1d | 1 |  |
| bOverride_SSRTAOTwoSidedFoliageThreshold | 0x1d | 1 |  |
| bOverride_SSRTAOBentNormalThreshold | 0x1d | 1 |  |
| bOverride_SSRTAONoiseStep | 0x1d | 1 |  |
| bOverride_SSRTAOStepSize | 0x1d | 1 |  |
| bOverride_SSRTAOFirstPersonStepSize | 0x1d | 1 |  |
| bOverride_SSRTAOFoliageStepSize | 0x1d | 1 |  |
| bOverride_SSRTAOFoliageNormalAdjust | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseTemporalBlendWeight | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseTemporalMomentBlendWeight | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseTemporalNormalTolerance | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseTemporalDepthTolerance | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseTemporalHistoryLength | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseSpatialAOSigma | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseSpatialDepthSigma | 0x1e | 1 |  |
| bOverride_SSRTAODenoiseSpatialNormalSigma | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousIteration | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousCopyIterationIndex | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousIterationStartKernelStep | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousAOSigma | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousDepthSigma | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousDepthWeightCutoff | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousNormalSigma | 0x1f | 1 |  |
| bOverride_SSRTAODenoiseATrousMinVarianceToDenoise | 0x20 | 1 |  |
| bOverride_RayTracingAO | 0x20 | 1 |  |
| bOverride_RayTracingAOSamplesPerPixel | 0x20 | 1 |  |
| bOverride_LPVIntensity | 0x20 | 1 |  |
| bOverride_LPVDirectionalOcclusionIntensity | 0x20 | 1 |  |
| bOverride_LPVDirectionalOcclusionRadius | 0x20 | 1 |  |
| bOverride_LPVDiffuseOcclusionExponent | 0x20 | 1 |  |
| bOverride_LPVSpecularOcclusionExponent | 0x20 | 1 |  |
| bOverride_LPVDiffuseOcclusionIntensity | 0x21 | 1 |  |
| bOverride_LPVSpecularOcclusionIntensity | 0x21 | 1 |  |
| bOverride_LPVSize | 0x21 | 1 |  |
| bOverride_LPVSecondaryOcclusionIntensity | 0x21 | 1 |  |
| bOverride_LPVSecondaryBounceIntensity | 0x21 | 1 |  |
| bOverride_LPVGeometryVolumeBias | 0x21 | 1 |  |
| bOverride_LPVVplInjectionBias | 0x21 | 1 |  |
| bOverride_LPVEmissiveInjectionIntensity | 0x21 | 1 |  |
| bOverride_LPVFadeRange | 0x22 | 1 |  |
| bOverride_LPVDirectionalOcclusionFadeRange | 0x22 | 1 |  |
| bOverride_IndirectLightingColor | 0x22 | 1 |  |
| bOverride_IndirectLightingIntensity | 0x22 | 1 |  |
| bOverride_ColorGradingIntensity | 0x22 | 1 |  |
| bOverride_ColorGradingLUT | 0x22 | 1 |  |
| bOverride_UseACEScc | 0x22 | 1 |  |
| bOverride_PCHighPrecisionLMT | 0x22 | 1 |  |
| bOverride_LMT_LUTIntensity | 0x23 | 1 |  |
| bOverride_LMT_LUT | 0x23 | 1 |  |
| bOverride_OutputDeviceRec709 | 0x23 | 1 |  |
| bOverride_DepthOfFieldFocalDistance | 0x23 | 1 |  |
| bOverride_MobileDepthOfFieldFocalDistance | 0x23 | 1 |  |
| bOverride_DepthOfFieldFstop | 0x23 | 1 |  |
| bOverride_DepthOfFieldMinFstop | 0x23 | 1 |  |
| bOverride_DepthOfFieldBladeCount | 0x23 | 1 |  |
| bOverride_DepthOfFieldSensorWidth | 0x24 | 1 |  |
| bOverride_DepthOfFieldSqueezeFactor | 0x24 | 1 |  |
| bOverride_DepthOfFieldDepthBlurRadius | 0x24 | 1 |  |
| bOverride_DepthOfFieldDepthBlurAmount | 0x24 | 1 |  |
| bOverride_DepthOfFieldFocalRegion | 0x24 | 1 |  |
| bOverride_DepthOfFieldNearTransitionRegion | 0x24 | 1 |  |
| bOverride_DepthOfFieldFarTransitionRegion | 0x24 | 1 |  |
| bOverride_DepthOfFieldScale | 0x24 | 1 |  |
| bOverride_DepthOfFieldNearBlurSize | 0x25 | 1 |  |
| bOverride_DepthOfFieldFarBlurSize | 0x25 | 1 |  |
| bOverride_MobileHQGaussian | 0x25 | 1 |  |
| bOverride_MobileDefaultUEHQGaussian | 0x25 | 1 |  |
| bOverride_MobileRadialBlur | 0x25 | 1 |  |
| bOverride_MobileGhostEffect | 0x25 | 1 |  |
| bOverride_DepthOfFieldOcclusion | 0x25 | 1 |  |
| bOverride_DepthOfFieldSkyFocusDistance | 0x25 | 1 |  |
| bOverride_DepthOfFieldVignetteSize | 0x26 | 1 |  |
| bOverride_MotionBlurAmount | 0x26 | 1 |  |
| bOverride_MotionBlurMax | 0x26 | 1 |  |
| bOverride_MotionBlurTargetFPS | 0x26 | 1 |  |
| bOverride_MotionBlurPerObjectSize | 0x26 | 1 |  |
| bOverride_EnableMobileMotionBlur | 0x26 | 1 |  |
| bOverride_MobileMotionBlurMaxSampleCount | 0x26 | 1 |  |
| bOverride_MobileMotionBlurVelocityScale | 0x26 | 1 |  |
| bOverride_MobileMotionBlurMaxVelocity | 0x27 | 1 |  |
| bOverride_MobileMotionBlurUseAABBMask | 0x27 | 1 |  |
| bOverride_MobileMotionBlurDepthMask | 0x27 | 1 |  |
| bOverride_MobileMotionBlurDepthMaskTransition | 0x27 | 1 |  |
| bOverride_MobileMotionBlurAABBMaskCenter | 0x27 | 1 |  |
| bOverride_MobileMotionBlurAABBMaskExtent | 0x27 | 1 |  |
| bOverride_MobileMotionBlurAABBMaskTransition | 0x27 | 1 |  |
| bOverride_MobileMotionBlurDisplayIntensity | 0x27 | 1 |  |
| bOverride_MobileMotionBlurUseVSVelocity | 0x28 | 1 |  |
| bOverride_MobileMotionBlurDownSampleFactor | 0x28 | 1 |  |
| bOverride_MobileMotionBlurAssumedDepth | 0x28 | 1 |  |
| bOverride_ScreenPercentage | 0x28 | 1 |  |
| bOverride_ScreenSpaceReflectionIntensity | 0x28 | 1 |  |
| bOverride_ScreenSpaceReflectionQuality | 0x28 | 1 |  |
| bOverride_ScreenSpaceReflectionMaxRoughness | 0x28 | 1 |  |
| bOverride_ScreenSpaceReflectionRoughnessScale | 0x28 | 1 |  |
| bOverride_ScreenRainDropBlurStrength | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurCullRadius | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurStaticSplit | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurStaticDropDensity | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurDynamicXSplit | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurDynamicYSplit | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurDynamicDropDensity | 0x29 | 1 |  |
| bOverride_ScreenRainDropBlurTest | 0x29 | 1 |  |
| bOverride_ReflectionsType | 0x2a | 1 |  |
| bOverride_RayTracingReflectionsMaxRoughness | 0x2a | 1 |  |
| bOverride_RayTracingReflectionsMaxBounces | 0x2a | 1 |  |
| bOverride_RayTracingReflectionsSamplesPerPixel | 0x2a | 1 |  |
| bOverride_RayTracingReflectionsShadows | 0x2a | 1 |  |
| bOverride_RayTracingReflectionsTranslucency | 0x2a | 1 |  |
| bOverride_TranslucencyType | 0x2a | 1 |  |
| bOverride_RayTracingTranslucencyMaxRoughness | 0x2a | 1 |  |
| bOverride_RayTracingTranslucencyMinReflectionThroughput | 0x2b | 1 |  |
| bOverride_RayTracingTranslucencyMinRefractionThroughput | 0x2b | 1 |  |
| bOverride_RayTracingTranslucencyEnableAbsorption | 0x2b | 1 |  |
| bOverride_RayTracingTranslucencyRefractionRays | 0x2b | 1 |  |
| bOverride_RayTracingTranslucencySamplesPerPixel | 0x2b | 1 |  |
| bOverride_RayTracingTranslucencyShadows | 0x2b | 1 |  |
| bOverride_RayTracingTranslucencyRefraction | 0x2b | 1 |  |
| bOverride_RayTracingGI | 0x2b | 1 |  |
| bOverride_RayTracingGIMaxBounces | 0x2c | 1 |  |
| bOverride_RayTracingGISamplesPerPixel | 0x2c | 1 |  |
| bOverride_GIDenoiseApplyAO | 0x2c | 1 |  |
| bOverride_GIDenoiseEnableTemporal | 0x2c | 1 |  |
| bOverride_GIDenoiseTemporalBlendWeight | 0x2c | 1 |  |
| bOverride_GIDenoiseTemporalMomentBlendWeight | 0x2c | 1 |  |
| bOverride_GIDenoiseTemporalNormalTolerance | 0x2c | 1 |  |
| bOverride_GIDenoiseTemporalDepthTolerance | 0x2c | 1 |  |
| bOverride_GIDenoiseColorClamp | 0x2d | 1 |  |
| bOverride_GIDenoiseHistoryLength | 0x2d | 1 |  |
| bOverride_GIDenoiseEnableATrous | 0x2d | 1 |  |
| bOverride_GIDenoiseATrousIteration | 0x2d | 1 |  |
| bOverride_GIDenoiseATrousCopyIteration | 0x2d | 1 |  |
| bOverride_GIDenoiseATrousSampleDepthAsNormal | 0x2d | 1 |  |
| bOverride_GIDenoiseATrousFilterWidth | 0x2d | 1 |  |
| bOverride_GIDenoiseATrousVarianceGain | 0x2d | 1 |  |
| bOverride_GIDenoiseATrousNormalTolerance | 0x2e | 1 |  |
| bOverride_GIDenoiseATrousDepthTolerance | 0x2e | 1 |  |
| bOverride_GIDenoiseATrousAOTolerance | 0x2e | 1 |  |
| bOverride_GIDenoiseSpatialFilterType | 0x2e | 1 |  |
| bOverride_GIDenoiseType | 0x2e | 1 |  |
| bOverride_GIDenoiseDebugType | 0x2e | 1 |  |
| bOverride_PathTracingMaxBounces | 0x2e | 1 |  |
| bOverride_PathTracingSamplesPerPixel | 0x2e | 1 |  |
| bOverride_RayTracingCausticsEnable | 0x2f | 1 |  |
| bOverride_RayTracingCausticsResolution | 0x2f | 1 |  |
| bOverride_RayTracingCausticsIntensity | 0x2f | 1 |  |
| bOverride_RayTracingCausticsMaxIntensity | 0x2f | 1 |  |
| bOverride_RayTracingCausticsMaxTraceDepth | 0x2f | 1 |  |
| bOverride_RayTracingCausticsFinalCullColorThreshold | 0x2f | 1 |  |
| bOverride_RayTracingCausticsMidCullColorThreshold | 0x2f | 1 |  |
| bOverride_RayTracingCausticsTranslucentReflectionMode | 0x2f | 1 |  |
| bOverride_RayTracingCausticsMaxScreenRadius | 0x30 | 1 |  |
| bOverride_RayTracingCausticsBufferScale | 0x30 | 1 |  |
| bOverride_RayTracingCausticsScatterDepthTolerance | 0x30 | 1 |  |
| bOverride_RayTracingCausticsSplatSize | 0x30 | 1 |  |
| bOverride_RayTracingCausticsEnableDispersion | 0x30 | 1 |  |
| bOverride_RayTracingCausticsDispersionSamples | 0x30 | 1 |  |
| bOverride_RayTracingCausticsAdaptivePhotonSize | 0x30 | 1 |  |
| bOverride_RayTracingCausticsAdaptiveVarianceGain | 0x30 | 1 |  |
| bOverride_RayTracingCausticsAdaptiveSmooth | 0x31 | 1 |  |
| bOverride_RayTracingCausticsAdaptiveMaxSample | 0x31 | 1 |  |
| bOverride_RayTracingCausticsAdaptiveUpdateSpeed | 0x31 | 1 |  |
| bOverride_RayTracingCausticsEnableTemporalFilter | 0x31 | 1 |  |
| bOverride_RayTracingCausticsJitter | 0x31 | 1 |  |
| bOverride_RayTracingCausticsTemporalStrength | 0x31 | 1 |  |
| bOverride_RayTracingCausticsTemporalColorTolerance | 0x31 | 1 |  |
| bOverride_RayTracingCausticsDebugLightData | 0x31 | 1 |  |
| bOverride_RayTracingCausticsDebugScreenData | 0x32 | 1 |  |
| bOverride_RayTracingCausticsDebugMaxPixelValue | 0x32 | 1 |  |
| bOverride_RayTracingCausticsDebugMapScale | 0x32 | 1 |  |
| bOverride_RayTracingCausticsDebugMaxPhotonCount | 0x32 | 1 |  |
| bOverride_RayTracingCausticsDebugMip | 0x32 | 1 |  |
| bOverride_RayTracingWaterCausticsType | 0x32 | 1 |  |
| bOverride_RayTracingWaterCausticsBufferScale | 0x32 | 1 |  |
| bOverride_RayTracingWaterCausticsFollowCamera | 0x32 | 1 |  |
| bOverride_RayTracingWaterCausticsLookAt | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsRange | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsColor | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsNumDenoisePasses | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsDispersionIntensity | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsDispersionOffset | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsReflectiveIntensity | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsReflectedRayTMax | 0x33 | 1 |  |
| bOverride_RayTracingWaterCausticsReflectedRayTMin | 0x34 | 1 |  |
| bOverride_RayTracingWaterCausticsRefractiveIntensity | 0x34 | 1 |  |
| bOverride_RayTracingWaterCausticsRefractedRayTMax | 0x34 | 1 |  |
| bOverride_RayTracingWaterCausticsRefractedRayTMin | 0x34 | 1 |  |
| bOverride_RayTracingWaterCausticsFresnelBaseReflectFraction | 0x34 | 1 |  |
| bOverride_RayTracingWaterCausticsReflectBackFaceCullingThreshold | 0x34 | 1 |  |
| bOverride_RayTracingWaterCausticsRefractBackFaceCullingThreshold | 0x34 | 1 |  |
| AutoExposureMethod | 0x35 | 1 | EAutoExposureMethod |
| bMobileHQGaussian | 0x36 | 1 |  |
| bMobileDefaultUEHQGaussian | 0x36 | 1 |  |
| BloomMethod | 0x37 | 1 | EBloomMethod |
| PPBlurMethod | 0x38 | 1 | EPPBlurMethod |
| PPEdgeDetectMethod | 0x39 | 1 | EPPEdgeDetectMethod |
| bMobileRadialBlur | 0x3a | 1 |  |
| mobileradialtint | 0x3c | 4 | PostProcessSettings |
| mobileradialstrength | 0x40 | 4 | PostProcessSettings |
| mobileradialcenter | 0x44 | 8 | Vector2D |
| mobileghostspeed | 0x4c | 8 | Vector2D |
| mobileghostblurtint | 0x54 | 4 | PostProcessSettings |
| bMobileGhostEffect | 0x58 | 1 |  |
| WhiteTemp | 0x5c | 4 | PostProcessSettings |
| WhiteTint | 0x60 | 4 | PostProcessSettings |
| ColorSaturation | 0x70 | 16 | Vector4 |
| ColorContrast | 0x80 | 16 | Vector4 |
| ColorGamma | 0x90 | 16 | Vector4 |
| ColorGain | 0xa0 | 16 | Vector4 |
| ColorOffset | 0xb0 | 16 | Vector4 |
| ColorSaturationShadows | 0xc0 | 16 | Vector4 |
| ColorContrastShadows | 0xd0 | 16 | Vector4 |
| ColorGammaShadows | 0xe0 | 16 | Vector4 |
| ColorGainShadows | 0xf0 | 16 | Vector4 |
| ColorOffsetShadows | 0x100 | 16 | Vector4 |
| ColorSaturationMidtones | 0x110 | 16 | Vector4 |
| ColorContrastMidtones | 0x120 | 16 | Vector4 |
| ColorGammaMidtones | 0x130 | 16 | Vector4 |
| ColorGainMidtones | 0x140 | 16 | Vector4 |
| ColorOffsetMidtones | 0x150 | 16 | Vector4 |
| ColorSaturationHighlights | 0x160 | 16 | Vector4 |
| ColorContrastHighlights | 0x170 | 16 | Vector4 |
| ColorGammaHighlights | 0x180 | 16 | Vector4 |
| ColorGainHighlights | 0x190 | 16 | Vector4 |
| ColorOffsetHighlights | 0x1a0 | 16 | Vector4 |
| ColorCorrectionHighlightsMin | 0x1b0 | 4 | PostProcessSettings |
| ColorCorrectionShadowsMax | 0x1b4 | 4 | PostProcessSettings |
| BlueCorrection | 0x1b8 | 4 | PostProcessSettings |
| DarknessCorrection | 0x1bc | 4 | PostProcessSettings |
| ExpandGamut | 0x1c0 | 4 | PostProcessSettings |
| FilmSlope | 0x1c4 | 4 | PostProcessSettings |
| FilmToe | 0x1c8 | 4 | PostProcessSettings |
| FilmShoulder | 0x1cc | 4 | PostProcessSettings |
| FilmBlackClip | 0x1d0 | 4 | PostProcessSettings |
| FilmWhiteClip | 0x1d4 | 4 | PostProcessSettings |
| Mobile_ACES_A | 0x1d8 | 4 | PostProcessSettings |
| Mobile_ACES_B | 0x1dc | 4 | PostProcessSettings |
| Mobile_ACES_C | 0x1e0 | 4 | PostProcessSettings |
| Mobile_ACES_D | 0x1e4 | 4 | PostProcessSettings |
| Mobile_ACES_E | 0x1e8 | 4 | PostProcessSettings |
| Mobile_LDR_ACES_A | 0x1ec | 4 | PostProcessSettings |
| Mobile_LDR_ACES_B | 0x1f0 | 4 | PostProcessSettings |
| Mobile_LDR_ACES_C | 0x1f4 | 4 | PostProcessSettings |
| Mobile_LDR_ACES_D | 0x1f8 | 4 | PostProcessSettings |
| Mobile_LDR_ACES_E | 0x1fc | 4 | PostProcessSettings |
| Mobile_CG_MasterTint | 0x200 | 16 | LinearColor |
| Mobile_CG_MasterSaturation | 0x210 | 4 | PostProcessSettings |
| Mobile_CG_Exposure | 0x214 | 4 | TwistConstraint |
| Mobile_CG_HdrScale | 0x218 | 4 | PostProcessSettings |
| Mobile_CG_Tint_K0 | 0x21c | 16 | LinearColor |
| Mobile_CG_Saturation_K0 | 0x22c | 4 | PostProcessSettings |
| Mobile_CG_Exposure_K0 | 0x230 | 4 | PostProcessSettings |
| Mobile_CG_Tint_K1 | 0x234 | 16 | LinearColor |
| Mobile_CG_Saturation_K1 | 0x244 | 4 | PostProcessSettings |
| Mobile_CG_Exposure_K1 | 0x248 | 4 | PostProcessSettings |
| Mobile_CG_Tint_K2 | 0x24c | 16 | LinearColor |
| Mobile_CG_Saturation_K2 | 0x25c | 4 | PostProcessSettings |
| Mobile_CG_Exposure_K2 | 0x260 | 4 | PostProcessSettings |
| MobileColorGradingLUT | 0x268 | 8 | Texture |
| MobileColorGradingLUTWeight | 0x270 | 4 | PostProcessSettings |
| FilmWhitePoint | 0x274 | 16 | LinearColor |
| FilmShadowTint | 0x284 | 16 | LinearColor |
| FilmShadowTintBlend | 0x294 | 4 | PostProcessSettings |
| FilmShadowTintAmount | 0x298 | 4 | PostProcessSettings |
| FilmSaturation | 0x29c | 4 | PostProcessSettings |
| FilmChannelMixerRed | 0x2a0 | 16 | LinearColor |
| FilmChannelMixerGreen | 0x2b0 | 16 | LinearColor |
| FilmChannelMixerBlue | 0x2c0 | 16 | LinearColor |
| FilmContrast | 0x2d0 | 4 | PostProcessSettings |
| FilmToeAmount | 0x2d4 | 4 | PostProcessSettings |
| FilmHealAmount | 0x2d8 | 4 | PostProcessSettings |
| FilmDynamicRange | 0x2dc | 4 | PostProcessSettings |
| SceneColorTint | 0x2e0 | 16 | LinearColor |
| SceneFringeIntensity | 0x2f0 | 4 | PostProcessSettings |
| ChromaticAberrationStartOffset | 0x2f4 | 4 | PostProcessSettings |
| ChromaticAberrationSCaleR | 0x2f8 | 4 | PostProcessSettings |
| ChromaticAberrationSCaleG | 0x2fc | 4 | PostProcessSettings |
| BloomIntensity | 0x300 | 4 | PostProcessSettings |
| BloomMaxLuminance | 0x304 | 4 | PostProcessSettings |
| BloomMaxLuminanceWithoutExposure | 0x308 | 4 | PostProcessSettings |
| BloomMaxLuminanceWithoutExposureEnabled | 0x30c | 1 |  |
| MobileBloomMaxLuminance | 0x310 | 4 | PostProcessSettings |
| MobileBloomMaxLuminanceWithoutExposure | 0x314 | 4 | PostProcessSettings |
| BloomThreshold | 0x318 | 4 | PostProcessSettings |
| BloomSizeScale | 0x31c | 4 | PostProcessSettings |
| Bloom1Size | 0x320 | 4 | PostProcessSettings |
| Bloom2Size | 0x324 | 4 | PostProcessSettings |
| Bloom3Size | 0x328 | 4 | PostProcessSettings |
| Bloom4Size | 0x32c | 4 | PostProcessSettings |
| Bloom5Size | 0x330 | 4 | PostProcessSettings |
| Bloom6Size | 0x334 | 4 | PostProcessSettings |
| Bloom1Tint | 0x338 | 16 | LinearColor |
| Bloom2Tint | 0x348 | 16 | LinearColor |
| Bloom3Tint | 0x358 | 16 | LinearColor |
| Bloom4Tint | 0x368 | 16 | LinearColor |
| Bloom5Tint | 0x378 | 16 | LinearColor |
| Bloom6Tint | 0x388 | 16 | LinearColor |
| MobileBloomTint | 0x398 | 16 | LinearColor |
| MobileBloomThreshold | 0x3a8 | 4 | MinimalViewInfo |
| BloomConvolutionSize | 0x3ac | 4 | PostProcessSettings |
| BloomConvolutionTexture | 0x3b0 | 8 | Texture2D |
| BloomConvolutionCenterUV | 0x3b8 | 8 | Vector2D |
| BloomConvolutionPreFilterMin | 0x3c0 | 4 | PostProcessSettings |
| BloomConvolutionPreFilterMax | 0x3c4 | 4 | PostProcessSettings |
| BloomConvolutionPreFilterMult | 0x3c8 | 4 | PostProcessSettings |
| BloomConvolutionBufferScale | 0x3cc | 4 | PostProcessSettings |
| BloomDirtMask | 0x3d0 | 8 | Texture |
| BloomDirtMaskIntensity | 0x3d8 | 4 | PostProcessSettings |
| BloomDirtMaskTint | 0x3dc | 16 | LinearColor |
| AmbientCubemapTint | 0x3ec | 16 | LinearColor |
| AmbientCubemapIntensity | 0x3fc | 4 | PostProcessSettings |
| AmbientCubemap | 0x400 | 8 | TextureCube |
| CameraShutterSpeed | 0x408 | 4 | PostProcessSettings |
| CameraISO | 0x40c | 4 | PostProcessSettings |
| DepthOfFieldFstop | 0x410 | 4 | PostProcessSettings |
| DepthOfFieldMinFstop | 0x414 | 4 | PostProcessSettings |
| DepthOfFieldBladeCount | 0x418 | 4 | PostProcessSettings |
| AutoExposureBias | 0x41c | 4 | PostProcessSettings |
| AutoExposureBiasBackup | 0x420 | 4 | PostProcessSettings |
| bOverride_AutoExposureBiasBackup | 0x424 | 1 |  |
| AutoExposureApplyPhysicalCameraExposure | 0x424 | 1 |  |
| AutoExposureBiasCurve | 0x428 | 8 | CurveFloat |
| AutoExposureMeterMask | 0x430 | 8 | Texture |
| AutoExposureLowPercent | 0x438 | 4 | PostProcessSettings |
| AutoExposureHighPercent | 0x43c | 4 | PostProcessSettings |
| AutoExposureMinBrightness | 0x440 | 4 | PostProcessSettings |
| AutoExposureMaxBrightness | 0x444 | 4 | PostProcessSettings |
| AutoExposureSpeedUp | 0x448 | 4 | PostProcessSettings |
| AutoExposureSpeedDown | 0x44c | 4 | PostProcessSettings |
| HistogramLogMin | 0x450 | 4 | PostProcessSettings |
| HistogramLogMax | 0x454 | 4 | PostProcessSettings |
| AutoExposureCalibrationConstant | 0x458 | 4 | PostProcessSettings |
| LocalExposureHighlightContrastScale | 0x45c | 4 | PostProcessSettings |
| LocalExposureShadowContrastScale | 0x460 | 4 | PostProcessSettings |
| LocalExposureHighlightContrastCurve | 0x468 | 8 | CurveFloat |
| LocalExposureShadowContrastCurve | 0x470 | 8 | CurveFloat |
| LocalExposureHighlightThreshold | 0x478 | 4 | PostProcessSettings |
| LocalExposureShadowThreshold | 0x47c | 4 | PostProcessSettings |
| LocalExposureDetailStrength | 0x480 | 4 | PostProcessSettings |
| LocalExposureBlurredLuminanceBlend | 0x484 | 4 | PostProcessSettings |
| LocalExposureBlurredLuminanceKernelSizePercent | 0x488 | 4 | PostProcessSettings |
| LocalExposureMiddleGreyBias | 0x48c | 4 | PostProcessSettings |
| MiddleGreyBiasCompensation | 0x490 | 1 |  |
| BlurRadius | 0x494 | 4 | PostProcessSettings |
| LensFlareMethod | 0x498 | 1 | ELensFlareMethod |
| LensFlareIntensity | 0x49c | 4 | PostProcessSettings |
| LensFlareTint | 0x4a0 | 16 | LinearColor |
| LensFlareBokehSize | 0x4b0 | 4 | PostProcessSettings |
| LensFlareThreshold | 0x4b4 | 4 | PostProcessSettings |
| LensFlareBokehShape | 0x4b8 | 8 | Texture |
| LensFlareLineWidth | 0x4c0 | 4 | PostProcessSettings |
| LensFlareLineLength | 0x4c4 | 4 | PostProcessSettings |
| LensFlareLineIntensity | 0x4c8 | 4 | PostProcessSettings |
| LensFlareLineTint | 0x4cc | 16 | LinearColor |
| LensFlareHalo | 0x4e0 | 8 | Texture |
| LensFlareHaloScaleMin | 0x4e8 | 4 | PostProcessSettings |
| LensFlareHaloScaleMax | 0x4ec | 4 | PostProcessSettings |
| LensFlareTints | 0x4f0 | 16 | LinearColor |
| LensFlareLocation | 0x500 | 4 | PostProcessSettings |
| LensFlareTints | 0x504 | 16 | LinearColor |
| LensFlareLocation | 0x514 | 4 | PostProcessSettings |
| LensFlareTints | 0x518 | 16 | LinearColor |
| LensFlareLocation | 0x528 | 4 | PostProcessSettings |
| LensFlareTints | 0x52c | 16 | LinearColor |
| LensFlareLocation | 0x53c | 4 | PostProcessSettings |
| LensFlareTints | 0x540 | 16 | LinearColor |
| LensFlareLocation | 0x550 | 4 | PostProcessSettings |
| LensFlareTints | 0x554 | 16 | LinearColor |
| LensFlareTints | 0x564 | 16 | LinearColor |
| LensFlareTints | 0x574 | 16 | LinearColor |
| bUseMobileLensFlare | 0x584 | 1 |  |
| MobileLensFlareIntensity | 0x588 | 4 | PostProcessSettings |
| MobileLensFlareTint | 0x58c | 16 | LinearColor |
| MobileLensFlareBokehSize | 0x59c | 4 | PostProcessSettings |
| LensFlareRandomSeed | 0x5a0 | 4 | PostProcessSettings |
| LensFlareFlareCount | 0x5a4 | 4 | PostProcessSettings |
| LensFlareMinPositionScale | 0x5a8 | 4 | PostProcessSettings |
| LensFlareMaxPositionScale | 0x5ac | 4 | PostProcessSettings |
| MobileLensFlareBokehShape | 0x5b0 | 8 | Texture |
| LensFlareIntensity2 | 0x5b8 | 4 | PostProcessSettings |
| LensFlareTint2 | 0x5bc | 16 | LinearColor |
| LensFlareBokehSize2 | 0x5cc | 4 | PostProcessSettings |
| LensFlareRandomSeed2 | 0x5d0 | 4 | PostProcessSettings |
| LensFlareFlareCount2 | 0x5d4 | 4 | PostProcessSettings |
| LensFlareMinPositionScale2 | 0x5d8 | 4 | PostProcessSettings |
| LensFlareMaxPositionScale2 | 0x5dc | 4 | PostProcessSettings |
| LensFlareBokehShape2 | 0x5e0 | 8 | Texture |
| LensFlareRayTint | 0x5e8 | 16 | LinearColor |
| LensFlareRaySliceCount | 0x5f8 | 4 | PostProcessSettings |
| LensFlareRayThreshold | 0x5fc | 4 | PostProcessSettings |
| LensFlareRayRandomSeed | 0x600 | 4 | PostProcessSettings |
| LensFlareRaySize | 0x604 | 4 | PostProcessSettings |
| LensFlareRayWidth | 0x608 | 4 | PostProcessSettings |
| LensFlareRayIntensity | 0x60c | 4 | PostProcessSettings |
| VignetteIntensity | 0x610 | 4 | PostProcessSettings |
| GrainJitter | 0x614 | 4 | PostProcessSettings |
| GrainIntensity | 0x618 | 4 | PostProcessSettings |
| AmbientOcclusionIntensity | 0x61c | 4 | PostProcessSettings |
| AmbientOcclusionStaticFraction | 0x620 | 4 | PostProcessSettings |
| AmbientOcclusionRadius | 0x624 | 4 | PostProcessSettings |
| AmbientOcclusionRadiusInWS | 0x628 | 1 |  |
| AmbientOcclusionFadeDistance | 0x62c | 4 | PostProcessSettings |
| AmbientOcclusionFadeRadius | 0x630 | 4 | PostProcessSettings |
| AmbientOcclusionDistance | 0x634 | 4 | PostProcessSettings |
| AmbientOcclusionPower | 0x638 | 4 | PostProcessSettings |
| AmbientOcclusionBias | 0x63c | 4 | PostProcessSettings |
| AmbientOcclusionQuality | 0x640 | 4 | PostProcessSettings |
| AmbientOcclusionMipBlend | 0x644 | 4 | PostProcessSettings |
| AmbientOcclusionMipScale | 0x648 | 4 | PostProcessSettings |
| AmbientOcclusionMipThreshold | 0x64c | 4 | PostProcessSettings |
| AmbientOcclusionTemporalBlendWeight | 0x650 | 4 | PostProcessSettings |
| SSRTAOThreshold | 0x654 | 4 | PostProcessSettings |
| SSRTAOTwoSidedFoliageThreshold | 0x658 | 4 | PostProcessSettings |
| SSRTAOBentNormalThreshold | 0x65c | 4 |  |
| SSRTAONoiseStep | 0x660 | 4 | PostProcessSettings |
| SSRTAOStepSize | 0x664 | 4 | PostProcessSettings |
| SSRTAOFirstPersonStepSize | 0x668 | 4 | PostProcessSettings |
| SSRTAOFoliageStepSize | 0x66c | 4 | PostProcessSettings |
| SSRTAOFoliageNormalAdjust | 0x670 | 4 | PostProcessSettings |
| SSRTAODenoiseTemporalBlendWeight | 0x674 | 4 | PostProcessSettings |
| SSRTAODenoiseTemporalMomentBlendWeight | 0x678 | 4 | PostProcessSettings |
| SSRTAODenoiseTemporalNormalTolerance | 0x67c | 4 | PostProcessSettings |
| SSRTAODenoiseTemporalDepthTolerance | 0x680 | 4 | PostProcessSettings |
| SSRTAODenoiseTemporalHistoryLength | 0x684 | 4 | PostProcessSettings |
| SSRTAODenoiseSpatialAOSigma | 0x688 | 4 | PostProcessSettings |
| SSRTAODenoiseSpatialDepthSigma | 0x68c | 4 | PostProcessSettings |
| SSRTAODenoiseSpatialNormalSigma | 0x690 | 4 | PostProcessSettings |
| SSRTAODenoiseATrousIteration | 0x694 | 4 | PostProcessSettings |
| SSRTAODenoiseATrousCopyIterationIndex | 0x698 | 4 | PostProcessSettings |
| SSRTAODenoiseATrousIterationStartKernelStep | 0x69c | 4 | PostProcessSettings |
| SSRTAODenoiseATrousAOSigma | 0x6a0 | 4 | PostProcessSettings |
| SSRTAODenoiseATrousDepthSigma | 0x6a4 | 4 | PostProcessSettings |
| SSRTAODenoiseATrousDepthWeightCutoff | 0x6a8 | 4 | PostProcessSettings |
| SSRTAODenoiseATrousNormalSigma | 0x6ac | 4 | PostProcessSettings |
| SSRTAODenoiseATrousMinVarianceToDenoise | 0x6b0 | 4 | PostProcessSettings |
| RayTracingAO | 0x6b4 | 1 |  |
| RayTracingAOSamplesPerPixel | 0x6b8 | 4 | PostProcessSettings |
| IndirectLightingColor | 0x6bc | 16 | LinearColor |
| IndirectLightingIntensity | 0x6cc | 4 | PostProcessSettings |
| RayTracingGIType | 0x6d0 | 1 | ERayTracingGlobalIlluminationType |
| RayTracingGIMaxBounces | 0x6d4 | 4 | PostProcessSettings |
| RayTracingGISamplesPerPixel | 0x6d8 | 4 | PostProcessSettings |
| RayTracingCausticsEnable | 0x6dc | 1 |  |
| RayTracingCausticsResolution | 0x6dd | 1 | ERayTracingMeshCausticsResolutionOverride |
| RayTracingCausticsIntensity | 0x6e0 | 4 | PostProcessSettings |
| RayTracingCausticsMaxIntensity | 0x6e4 | 4 | PostProcessSettings |
| RayTracingCausticsMaxTraceDepth | 0x6e8 | 4 | PostProcessSettings |
| RayTracingCausticsFinalCullColorThreshold | 0x6ec | 4 | PostProcessSettings |
| RayTracingCausticsMidCullColorThreshold | 0x6f0 | 4 | PostProcessSettings |
| RayTracingCausticsTranslucentReflectionMode | 0x6f4 | 1 | ERayTracingMeshCausticsTranslucentReflectionMode |
| RayTracingCausticsMaxScreenRadius | 0x6f8 | 4 | PostProcessSettings |
| RayTracingCausticsBufferScale | 0x6fc | 1 | ERayTracingMeshCausticsBufferScale |
| RayTracingCausticsScatterDepthTolerance | 0x700 | 4 | PostProcessSettings |
| RayTracingCausticsSplatSize | 0x704 | 4 | PostProcessSettings |
| RayTracingCausticsEnableDispersion | 0x708 | 1 |  |
| RayTracingCausticsDispersionSamples | 0x70c | 4 | PostProcessSettings |
| RayTracingCausticsAdaptivePhotonSize | 0x710 | 4 | PostProcessSettings |
| RayTracingCausticsAdaptiveVarianceGain | 0x714 | 4 | PostProcessSettings |
| RayTracingCausticsAdaptiveSmooth | 0x718 | 4 | PostProcessSettings |
| RayTracingCausticsAdaptiveMaxSample | 0x71c | 4 | PostProcessSettings |
| RayTracingCausticsAdaptiveUpdateSpeed | 0x720 | 4 | PostProcessSettings |
| RayTracingCausticsEnableTemporalFilter | 0x724 | 1 |  |
| RayTracingCausticsJitter | 0x728 | 4 | PostProcessSettings |
| RayTracingCausticsTemporalStrength | 0x72c | 4 | PostProcessSettings |
| RayTracingCausticsTemporalColorTolerance | 0x730 | 4 | PostProcessSettings |
| RayTracingCausticsDebugLightData | 0x734 | 1 | ERayTracingMeshCausticsDebugLightData |
| RayTracingCausticsDebugScreenData | 0x735 | 1 | ERayTracingMeshCausticsDebugScreenData |
| RayTracingCausticsDebugMaxPixelValue | 0x738 | 4 | PostProcessSettings |
| RayTracingCausticsDebugMapScale | 0x73c | 4 | PostProcessSettings |
| RayTracingCausticsDebugMaxPhotonCount | 0x740 | 4 | PostProcessSettings |
| RayTracingCausticsDebugMip | 0x744 | 4 | PostProcessSettings |
| GIDenoiseApplyAO | 0x748 | 1 |  |
| GIDenoiseEnableTemporal | 0x748 | 1 |  |
| GIDenoiseTemporalBlendWeight | 0x74c | 4 | PostProcessSettings |
| GIDenoiseTemporalMomentBlendWeight | 0x750 | 4 | PostProcessSettings |
| GIDenoiseTemporalNormalTolerance | 0x754 | 4 | PostProcessSettings |
| GIDenoiseTemporalDepthTolerance | 0x758 | 4 | PostProcessSettings |
| GIDenoiseColorClamp | 0x75c | 4 | PostProcessSettings |
| GIDenoiseHistoryLength | 0x760 | 4 | PostProcessSettings |
| GIDenoiseEnableATrous | 0x764 | 1 |  |
| GIDenoiseATrousIteration | 0x768 | 4 | PostProcessSettings |
| GIDenoiseATrousCopyIteration | 0x76c | 4 | PostProcessSettings |
| GIDenoiseATrousSampleDepthAsNormal | 0x770 | 1 |  |
| GIDenoiseATrousFilterWidth | 0x774 | 4 | PostProcessSettings |
| GIDenoiseATrousVarianceGain | 0x778 | 4 | PostProcessSettings |
| GIDenoiseATrousNormalTolerance | 0x77c | 4 | PostProcessSettings |
| GIDenoiseATrousDepthTolerance | 0x780 | 4 | PostProcessSettings |
| GIDenoiseATrousAOTolerance | 0x784 | 4 | PostProcessSettings |
| GIDenoiseSpatialFilterType | 0x788 | 1 | ERayTracingGIDenoiseSpatialFilterType |
| GIDenoiseType | 0x789 | 1 | ERayTracingGIDenoiseType |
| GIDenoiseDebugType | 0x78a | 1 | ERayTracingGIDenoiseDebugType |
| RayTracingWaterCausticsType | 0x78b | 1 | ERayTracingWaterCausticsType |
| RayTracingWaterCausticsBufferScale | 0x78c | 1 | ERayTracingWaterCausticsBufferScale |
| RayTracingWaterCausticsFollowCamera | 0x78d | 1 |  |
| RayTracingWaterCausticsLookAt | 0x790 | 12 | Vector |
| RayTracingWaterCausticsRange | 0x79c | 12 | Vector |
| RayTracingWaterCausticsColor | 0x7a8 | 16 | LinearColor |
| RayTracingWaterCausticsNumDenoisePasses | 0x7b8 | 4 | PostProcessSettings |
| RayTracingWaterCausticsDispersionIntensity | 0x7bc | 4 | PostProcessSettings |
| RayTracingWaterCausticsDispersionOffset | 0x7c0 | 4 | PostProcessSettings |
| RayTracingWaterCausticsReflectiveIntensity | 0x7c4 | 4 | PostProcessSettings |
| RayTracingWaterCausticsReflectedRayTMax | 0x7c8 | 4 | PostProcessSettings |
| RayTracingWaterCausticsReflectedRayTMin | 0x7cc | 4 | PostProcessSettings |
| RayTracingWaterCausticsRefractiveIntensity | 0x7d0 | 4 | PostProcessSettings |
| RayTracingWaterCausticsRefractedRayTMax | 0x7d4 | 4 | PostProcessSettings |
| RayTracingWaterCausticsRefractedRayTMin | 0x7d8 | 4 | PostProcessSettings |
| RayTracingWaterCausticsFresnelBaseReflectFraction | 0x7dc | 4 | PostProcessSettings |
| RayTracingWaterCausticsReflectBackFaceCullingThreshold | 0x7e0 | 4 | PostProcessSettings |
| RayTracingWaterCausticsRefractBackFaceCullingThreshold | 0x7e4 | 4 | PostProcessSettings |
| ColorGradingIntensity | 0x7e8 | 4 | PostProcessSettings |
| ColorGradingLUT | 0x7f0 | 8 | Texture |
| UseACEScc | 0x7f8 | 1 |  |
| PCHighPrecisionLMT | 0x7f9 | 1 |  |
| LMT_LUTIntensity | 0x7fc | 4 | PostProcessSettings |
| LMT_LUT | 0x800 | 8 | Texture |
| OutputDeviceRec709 | 0x808 | 1 |  |
| DepthOfFieldSensorWidth | 0x80c | 4 | PostProcessSettings |
| DepthOfFieldSqueezeFactor | 0x810 | 4 | PostProcessSettings |
| DepthOfFieldFocalDistance | 0x814 | 4 | PostProcessSettings |
| DepthOfFieldDepthBlurAmount | 0x818 | 4 | PostProcessSettings |
| DepthOfFieldDepthBlurRadius | 0x81c | 4 | PostProcessSettings |
| DepthOfFieldFocalRegion | 0x820 | 4 | PostProcessSettings |
| MobileDepthOfFieldFocalDistance | 0x824 | 4 | PostProcessSettings |
| DepthOfFieldNearTransitionRegion | 0x828 | 4 | PostProcessSettings |
| DepthOfFieldFarTransitionRegion | 0x82c | 4 | PostProcessSettings |
| DepthOfFieldScale | 0x830 | 4 | PostProcessSettings |
| DepthOfFieldNearBlurSize | 0x834 | 4 | PostProcessSettings |
| DepthOfFieldFarBlurSize | 0x838 | 4 | PostProcessSettings |
| DepthOfFieldOcclusion | 0x83c | 4 | PostProcessSettings |
| DepthOfFieldSkyFocusDistance | 0x840 | 4 | PostProcessSettings |
| DepthOfFieldVignetteSize | 0x844 | 4 | PostProcessSettings |
| ScreenRainDropBlurStrength | 0x848 | 4 | PostProcessSettings |
| ScreenRainDropBlurCullRadius | 0x84c | 4 | PostProcessSettings |
| ScreenRainDropBlurStaticSplit | 0x850 | 4 | PostProcessSettings |
| ScreenRainDropBlurStaticDropDensity | 0x854 | 4 | PostProcessSettings |
| ScreenRainDropBlurDynamicXSplit | 0x858 | 4 | PostProcessSettings |
| ScreenRainDropBlurDynamicYSplit | 0x85c | 4 | PostProcessSettings |
| ScreenRainDropBlurDynamicDropDensity | 0x860 | 4 | PostProcessSettings |
| ScreenRainDropBlurTest | 0x864 | 4 | PostProcessSettings |
| MotionBlurAmount | 0x868 | 4 | PostProcessSettings |
| MotionBlurMax | 0x86c | 4 | PostProcessSettings |
| MotionBlurTargetFPS | 0x870 | 4 | PostProcessSettings |
| MotionBlurPerObjectSize | 0x874 | 4 | PostProcessSettings |
| bEnableMobileMotionBlur | 0x878 | 1 |  |
| MobileMotionBlurMaxSampleCount | 0x87c | 4 | PostProcessSettings |
| MobileMotionBlurVelocityScale | 0x880 | 4 | PostProcessSettings |
| MobileMotionBlurMaxVelocity | 0x884 | 4 | PostProcessSettings |
| bMobileMotionBlurUseAABBMask | 0x888 | 1 |  |
| MobileMotionBlurDepthMask | 0x88c | 4 | PostProcessSettings |
| MobileMotionBlurDepthMaskTransition | 0x890 | 4 | PostProcessSettings |
| MobileMotionBlurAABBMaskCenter | 0x894 | 8 | Vector2D |
| MobileMotionBlurAABBMaskExtent | 0x89c | 8 | Vector2D |
| MobileMotionBlurAABBMaskTransition | 0x8a4 | 4 | PostProcessSettings |
| bMobileMotionBlurDisplayIntensity | 0x8a8 | 1 |  |
| bMobileMotionBlurUseVSVelocity | 0x8a8 | 1 |  |
| MobileMotionBlurDownSampleFactor | 0x8ac | 4 | PostProcessSettings |
| MobileMotionBlurAssumedDepth | 0x8b0 | 4 | PostProcessSettings |
| LPVIntensity | 0x8b4 | 4 | PostProcessSettings |
| LPVVplInjectionBias | 0x8b8 | 4 | PostProcessSettings |
| LPVSize | 0x8bc | 4 | PostProcessSettings |
| LPVSecondaryOcclusionIntensity | 0x8c0 | 4 | PostProcessSettings |
| LPVSecondaryBounceIntensity | 0x8c4 | 4 | PostProcessSettings |
| LPVGeometryVolumeBias | 0x8c8 | 4 | PostProcessSettings |
| LPVEmissiveInjectionIntensity | 0x8cc | 4 | PostProcessSettings |
| LPVDirectionalOcclusionIntensity | 0x8d0 | 4 | PostProcessSettings |
| LPVDirectionalOcclusionRadius | 0x8d4 | 4 | PostProcessSettings |
| LPVDiffuseOcclusionExponent | 0x8d8 | 4 | PostProcessSettings |
| LPVSpecularOcclusionExponent | 0x8dc | 4 | PostProcessSettings |
| LPVDiffuseOcclusionIntensity | 0x8e0 | 4 | PostProcessSettings |
| LPVSpecularOcclusionIntensity | 0x8e4 | 4 | PostProcessSettings |
| ReflectionsType | 0x8e8 | 1 | EReflectionsType |
| ReflectionMethod | 0x8e9 | 1 | EReflectionMethod |
| LumenReflectionQuality | 0x8ec | 4 | PostProcessSettings |
| LumenReflectionsScreenTraces | 0x8f0 | 1 |  |
| LumenFrontLayerTranslucencyReflections | 0x8f0 | 1 |  |
| LumenMaxRoughnessToTraceReflections | 0x8f4 | 4 | PostProcessSettings |
| LumenMaxReflectionBounces | 0x8f8 | 4 | PostProcessSettings |
| LumenMaxRefractionBounces | 0x8fc | 4 | PostProcessSettings |
| ScreenSpaceReflectionIntensity | 0x900 | 4 | PostProcessSettings |
| ScreenSpaceReflectionQuality | 0x904 | 4 | PostProcessSettings |
| ScreenSpaceReflectionMaxRoughness | 0x908 | 4 | PostProcessSettings |
| RayTracingReflectionsMaxRoughness | 0x90c | 4 | PostProcessSettings |
| RayTracingReflectionsMaxBounces | 0x910 | 4 | PostProcessSettings |
| RayTracingReflectionsSamplesPerPixel | 0x914 | 4 | PostProcessSettings |
| RayTracingReflectionsShadows | 0x918 | 1 | EReflectedAndRefractedRayTracedShadows |
| RayTracingReflectionsTranslucency | 0x919 | 1 |  |
| TranslucencyType | 0x91a | 1 | ETranslucencyType |
| RayTracingTranslucencyMaxRoughness | 0x91c | 4 | PostProcessSettings |
| RayTracingTranslucencyMinReflectionThroughput | 0x920 | 4 | PostProcessSettings |
| RayTracingTranslucencyMinRefractionThroughput | 0x924 | 4 | PostProcessSettings |
| RayTracingTranslucencyEnableAbsorption | 0x928 | 1 |  |
| RayTracingTranslucencyRefractionRays | 0x92c | 4 | PostProcessSettings |
| RayTracingTranslucencySamplesPerPixel | 0x930 | 4 | PostProcessSettings |
| RayTracingTranslucencyShadows | 0x934 | 1 | EReflectedAndRefractedRayTracedShadows |
| RayTracingTranslucencyRefraction | 0x935 | 1 |  |
| PathTracingMaxBounces | 0x938 | 4 | PostProcessSettings |
| PathTracingSamplesPerPixel | 0x93c | 4 | PostProcessSettings |
| LPVFadeRange | 0x940 | 4 | PostProcessSettings |
| LPVDirectionalOcclusionFadeRange | 0x944 | 4 | PostProcessSettings |
| ScreenPercentage | 0x948 | 4 | PostProcessSettings |
| DynamicGlobalIlluminationMethod | 0x94c | 1 | EDynamicGlobalIlluminationMethod |
| LumenRayLightingMode | 0x94d | 1 | ELumenRayLightingModeOverride |
| LumenSceneLightingQuality | 0x950 | 4 | PostProcessSettings |
| LumenSceneDetail | 0x954 | 4 | PostProcessSettings |
| LumenSceneViewDistance | 0x958 | 4 | PostProcessSettings |
| LumenSceneLightingUpdateSpeed | 0x95c | 4 | PostProcessSettings |
| LumenFinalGatherQuality | 0x960 | 4 | PostProcessSettings |
| LumenFinalGatherLightingUpdateSpeed | 0x964 | 4 | PostProcessSettings |
| LumenFinalGatherScreenTraces | 0x968 | 1 |  |
| LumenMaxTraceDistance | 0x96c | 4 | PostProcessSettings |
| LumenDiffuseColorBoost | 0x970 | 4 | PostProcessSettings |
| LumenSkylightLeaking | 0x974 | 4 | PostProcessSettings |
| LumenFullSkylightLeakingDistance | 0x978 | 4 | PostProcessSettings |
| LumenSurfaceCacheResolution | 0x97c | 4 | PostProcessSettings |
| LumenSSRTAOStepSize | 0x980 | 4 | PostProcessSettings |
| LumenSSRTAOFoliageStepSize | 0x984 | 4 | PostProcessSettings |
| LumenSSRTAONoiseStep | 0x988 | 4 | PostProcessSettings |
| LumenSSRTAOBentNormalThreshold | 0x98c | 4 | PostProcessSettings |
| LumenSSRTAOThreshold | 0x990 | 4 | PostProcessSettings |
| LumenSSRTAOTwoSidedFoliageThreshold | 0x994 | 4 | WeightedBlendable |
| WeightedBlendables | 0x998 | 16 | WeightedBlendables |

## PrecomputedLightInstanceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Transform | 0xb0 | 48 | Transform |
| LightGuid | 0xe0 | 16 | Guid |
| PreviewShadowMapChannel | 0xf0 | 4 | DynamicTextureInstance |

## PrecomputedSkyLightInstanceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LightGuid | 0xa8 | 16 | Guid |
| AverageBrightness | 0xb8 | 4 | TentDistribution |

## PredictProjectilePathPointData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x0 | 12 | Vector |
| Velocity | 0xc | 12 | Vector |
| Time | 0x18 | 4 | ForceFeedbackParameters |

## PredictionKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Current | 0x0 | 2 | PredictionKey |
| Base | 0x2 | 2 | ActiveGameplayEffect |
| PredictiveConnection | 0x8 | 8 | PackageMap |
| bIsStale | 0x10 | 1 |  |
| bIsServerInitiated | 0x11 | 1 |  |

## PreviewAttachedObjectPair

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AttachedObject | 0x0 | 40 | Object |
| Object | 0x28 | 8 | Object |
| AttachedTo | 0x30 | 8 |  |

## PrimaryAssetId

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PrimaryAssetType | 0x0 | 8 | PrimaryAssetType |
| PrimaryAssetName | 0x8 | 8 | SoftObjectPath |

## PrimaryAssetRules

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Priority | 0x0 | 4 | PrimaryAssetRules |
| ChunkID | 0x4 | 4 | AOReplacingSourceSection |
| bApplyRecursively | 0x8 | 1 |  |
| CookRule | 0x9 | 1 | EPrimaryAssetCookRule |

## PrimaryAssetRulesCustomOverride

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PrimaryAssetType | 0x0 | 8 | PrimaryAssetType |
| FilterDirectory | 0x8 | 16 | DirectoryPath |
| FilterString | 0x18 | 16 | PrimaryAssetRules |
| Rules | 0x28 | 12 | PrimaryAssetRules |

## PrimaryAssetType

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | IntPoint |

## PrimaryAssetTypeInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PrimaryAssetType | 0x0 | 8 |  |
| AssetBaseClass | 0x8 | 40 | Class |
| AssetBaseClassLoaded | 0x30 | 8 | Class |
| bHasBlueprintClasses | 0x38 | 1 |  |
| bIsEditorOnly | 0x39 | 1 |  |
| Directories | 0x40 | 16 |  |
| SpecificAssets | 0x50 | 16 |  |
| Rules | 0x60 | 12 | PrimaryAssetRules |
| AssetScanPaths | 0x70 | 16 |  |
| bIsDynamicAsset | 0x80 | 1 |  |
| NumberOfAssets | 0x84 | 4 | AssetManagerRedirect |

## PrimitiveComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MinDrawDistance | 0x248 | 4 | PrimitiveComponent |
| LDMaxDrawDistance | 0x24c | 4 | PrimitiveComponent |
| CachedMaxDrawDistance | 0x250 | 4 | PrimitiveComponent |
| DepthPriorityGroup | 0x254 | 1 | ESceneDepthPriorityGroup |
| ViewOwnerDepthPriorityGroup | 0x255 | 1 | ESceneDepthPriorityGroup |
| IndirectLightingCacheQuality | 0x256 | 1 | EIndirectLightingCacheQuality |
| LightmapType | 0x257 | 1 | ELightmapType |
| bEnableAOLightmap | 0x258 | 1 |  |
| bMobileUseGlobalLocalLights | 0x258 | 1 |  |
| bForceUsePrtForHD | 0x258 | 1 |  |
| bForceUsePrtForMobile | 0x258 | 1 |  |
| bUseMaxLODAsImposter | 0x258 | 1 |  |
| bBatchImpostersAsInstances | 0x258 | 1 |  |
| ShadowCacheInvalidationBehavior | 0x259 | 1 | EShadowCacheInvalidationBehavior |
| bNeverDistanceCull | 0x25a | 1 |  |
| bAlwaysCreatePhysicsState | 0x25a | 1 |  |
| bDFMCreatePhysicsState | 0x25a | 1 |  |
| bDFMCreateSimulationPhysicsState | 0x25a | 1 |  |
| bDFMSimulationUpdateTransformFromGameThread | 0x25b | 1 |  |
| bDFMAsyncPhysicsStateCreated | 0x25b | 1 |  |
| bSkipCalcLocalBounds | 0x25b | 1 |  |
| bGenerateOverlapEvents | 0x268 | 1 |  |
| bMultiBodyOverlap | 0x268 | 1 |  |
| bTraceComplexOnMove | 0x268 | 1 |  |
| bReturnMaterialOnMove | 0x268 | 1 |  |
| bUseViewOwnerDepthPriorityGroup | 0x268 | 1 |  |
| bAllowCullDistanceVolume | 0x268 | 1 |  |
| bHasMotionBlurVelocityMeshes | 0x268 | 1 |  |
| bVisibleInReflectionCaptures | 0x268 | 1 |  |
| bReflectionCapturesCubemapBlend | 0x269 | 1 |  |
| bBlendReflectionCapturesPOI | 0x269 | 1 |  |
| bAutoUpdateCachedReflection | 0x269 | 1 |  |
| bForceSkylightReflection | 0x269 | 1 |  |
| bOnlySkylight | 0x269 | 1 |  |
| bVisibleInRayTracing | 0x269 | 1 |  |
| bForceHiddenVisibleInRayTracing | 0x269 | 1 |  |
| bVisibleInRayTracingTag | 0x269 | 1 |  |
| RayTracingCullingDistance | 0x26c | 4 | PrimitiveComponent |
| bVisibleInLumenSceneTag | 0x270 | 1 |  |
| bOnlyVisibleInFPRayTracing | 0x270 | 1 |  |
| LumenSceneCullingDistance | 0x274 | 4 | PrimitiveComponent |
| bRenderInMainPass | 0x278 | 1 |  |
| bRenderInDepthPass | 0x278 | 1 |  |
| bReceivesDecals | 0x278 | 1 |  |
| bOwnerNoSee | 0x278 | 1 |  |
| bOnlyOwnerSee | 0x278 | 1 |  |
| bTreatAsBackgroundForOcclusion | 0x278 | 1 |  |
| bUseAsOccluder | 0x278 | 1 |  |
| bNotAsSocOccluder | 0x278 | 1 |  |
| bDisallowOcclusionCull | 0x279 | 1 |  |
| bDisallowAuxRHI | 0x279 | 1 |  |
| bSelectable | 0x279 | 1 |  |
| bWantsEditorEffects | 0x279 | 1 |  |
| bForceMipStreaming | 0x279 | 1 |  |
| bHasPerInstanceHitProxies | 0x279 | 1 |  |
| CastShadow | 0x279 | 1 |  |
| ForceCastShadowInBake | 0x279 | 1 |  |
| CastShadowMask | 0x280 | 8 | PrimitiveComponent |
| bAffectDynamicIndirectLighting | 0x288 | 1 |  |
| bAffectIndirectLightingWhileHidden | 0x288 | 1 |  |
| bAffectDistanceFieldLighting | 0x288 | 1 |  |
| bCastDynamicShadow | 0x288 | 1 |  |
| bCastStationaryPerObjectShadow | 0x288 | 1 |  |
| bUsePRTAttenuationForMobile | 0x288 | 1 |  |
| bCastCachedMapTileShadow | 0x288 | 1 |  |
| bUpdateCachedMapTileShadowEveryFrame | 0x289 | 1 |  |
| bCastStaticShadow | 0x28a | 1 |  |
| bCastVolumetricTranslucentShadow | 0x28a | 1 |  |
| bSelfShadowOnly | 0x28a | 1 |  |
| bOverrideCastFarShadow | 0x28a | 1 |  |
| bCastFarShadow | 0x28a | 1 |  |
| CastRainShadow | 0x28a | 1 |  |
| bCastPreBakeShadow | 0x28a | 1 |  |
| bOverrideLODShadowBias | 0x28a | 1 |  |
| bLODShadowBias | 0x28b | 1 |  |
| LODShadowBiasScale | 0x28c | 4 | PrimitiveComponent |
| LocalLightShadowBias | 0x290 | 4 | PrimitiveComponent |
| bCastFirstPersonShadow | 0x294 | 1 |  |
| bReceiveFirstPersonShadow | 0x294 | 1 |  |
| bCastThirdPersonShadow | 0x294 | 1 |  |
| bCastInsetShadow | 0x294 | 1 |  |
| bCastCinematicShadow | 0x294 | 1 |  |
| bCastHiddenShadow | 0x294 | 1 |  |
| bCastShadowAsTwoSided | 0x294 | 1 |  |
| bLightAsIfStatic | 0x294 | 1 |  |
| bLightAttachmentsAsGroup | 0x295 | 1 |  |
| bExcludeFromLightAttachmentGroup | 0x295 | 1 |  |
| bReceiveMobileCSMShadows | 0x295 | 1 |  |
| bSingleSampleShadowFromStationaryLights | 0x295 | 1 |  |
| bIgnoreRadialImpulse | 0x295 | 1 |  |
| bIgnoreRadialForce | 0x295 | 1 |  |
| bApplyImpulseOnDamage | 0x295 | 1 |  |
| bReplicatePhysicsToAutonomousProxy | 0x295 | 1 |  |
| AlwaysLoadOnClient | 0x296 | 1 |  |
| AlwaysLoadOnServer | 0x296 | 1 |  |
| bUseEditorCompositing | 0x296 | 1 |  |
| bRenderCustomDepth | 0x296 | 1 |  |
| bEvaluateRayTracingWaterCaustics | 0x296 | 1 |  |
| bForceHighQualityShading | 0x296 | 1 |  |
| bNoBakeLightingMap | 0x296 | 1 |  |
| bEnableProbeAnchorOffset | 0x296 | 1 |  |
| bRayTracingFarField | 0x297 | 1 |  |
| bEnableWindEffect | 0x297 | 1 |  |
| bHasCustomNavigableGeometry | 0x29a | 1 | EHasCustomNavigableGeometry |
| RenderMatrixMode | 0x29b | 1 | ERenderMatrixMode |
| UvdragRatio | 0x2a0 | 4 | PrimitiveComponent |
| bThin | 0x2a4 | 1 |  |
| CanCharacterStepUpOn | 0x2a5 | 1 | ECanBeCharacterBase |
| LightingChannels | 0x2a6 | 1 | LightingChannels |
| bUseDecalIgnoreChannel | 0x2a7 | 1 |  |
| CustomDepthStencilWriteMask | 0x2a8 | 1 | ERendererStencilMask |
| CustomDepthStencilValue | 0x2ac | 4 | PrimitiveComponent |
| PreferredWorldScaleType | 0x2b0 | 1 | EPreferredWorldScaleType |
| CustomPrimitiveData | 0x2b8 | 16 | CustomPrimitiveData |
| TranslucencySortPriority | 0x2c8 | 4 | PrimitiveComponent |
| VisibilityId | 0x2cc | 4 | PrimitiveComponent |
| RuntimeVirtualTextures | 0x2d0 | 16 |  |
| VirtualTextureLodBias | 0x2e0 | 1 | PrimitiveComponent |
| VirtualTextureCullMips | 0x2e1 | 1 | PrimitiveComponent |
| VirtualTextureMinCoverage | 0x2e2 | 1 | PrimitiveComponent |
| VirtualTextureRenderPassType | 0x2e3 | 1 | ERuntimeVirtualTextureMainPassType |
| VirtualTextureRenderLayerType | 0x2e4 | 1 | ERuntimeVirtualTextureLayerType |
| VirtualTextureRenderPriority | 0x2e5 | 1 |  |
| LpvBiasMultiplier | 0x2ec | 4 | PrimitiveComponent |
| SoftDepthOffSet | 0x2f0 | 4 | PrimitiveComponent |
| BoundsScale | 0x2fc | 4 | PrimitiveComponent |
| MoveIgnoreActors | 0x310 | 16 |  |
| MoveIgnoreComponents | 0x320 | 16 |  |
| BodyInstance | 0x340 | 288 | BodyInstance |
| OnComponentHit | 0x460 | 1 |  |
| OnComponentBeginOverlap | 0x461 | 1 |  |
| OnComponentEndOverlap | 0x462 | 1 |  |
| OnComponentWake | 0x463 | 1 |  |
| OnComponentSleep | 0x464 | 1 |  |
| OnBeginCursorOver | 0x466 | 1 |  |
| OnEndCursorOver | 0x467 | 1 |  |
| OnClicked | 0x468 | 1 |  |
| OnReleased | 0x469 | 1 |  |
| OnInputTouchBegin | 0x46a | 1 |  |
| OnInputTouchEnd | 0x46b | 1 |  |
| OnInputTouchEnter | 0x46c | 1 |  |
| OnInputTouchLeave | 0x46d | 1 |  |
| LODParentPrimitive | 0x488 | 8 | PrimitiveComponent |
| LazyLODParent | 0x490 | 28 | PrimitiveComponent |
| LazyLODChildren | 0x4b0 | 16 |  |
| PrimitiveHLODLevel | 0x4c0 | 1 | PrimitiveComponent |
| bForceOutputVelocities | 0x4c1 | 1 |  |
| ProbeAnchorOffset | 0x4c4 | 12 | Vector |
| bTetContributeGI | 0x4d0 | 1 |  |
| bTetReceiveGI | 0x4d0 | 1 |  |
| bTetReceiveStaticGI | 0x4d0 | 1 |  |
| StaticTetData | 0x4e0 | 176 | TetCachedABC |
| CullingDistance | 0x590 | 4 | PrimitiveComponent |
| CullingScreenSize | 0x594 | 4 | PrimitiveComponent |
| bOverrideEmissiveGI | 0x598 | 1 |  |
| OverrideEmissiveGIColor | 0x59c | 4 | Color |
| OverrideEmissiveGIIntensity | 0x5a0 | 4 |  |
| bNoEmissiveScreenTraceGI | 0x5a4 | 1 |  |

## PrimitiveComponentInstanceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ComponentTransform | 0xb0 | 48 | Transform |
| VisibilityId | 0xe0 | 4 | PreviewAttachedObjectPair |
| LODParent | 0xe8 | 8 | PrimitiveComponent |

## PrimitiveMaterialRef

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Primitive | 0x0 | 8 | PrimitiveComponent |
| Decal | 0x8 | 8 | DecalComponent |
| ElementIndex | 0x10 | 4 | AnimSlotInfo |

## PropertyReplicationHandler

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PropertyReplicationComponent | 0x0 | 8 | PropertyReplicationComponent |
| ObjectIndex | 0x8 | 4 | DFMCharacter |

## PurchaseInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Identifier | 0x0 | 16 | TOD_GiAdjust |
| DisplayName | 0x10 | 16 | PurchaseInfo |
| DisplayDescription | 0x20 | 16 | PurchaseInfo |
| DisplayPrice | 0x30 | 16 | MaterialCluster |

## Quat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | Quat |
| Y | 0x4 | 4 | Quat |
| Z | 0x8 | 4 | Quat |
| W | 0xc | 4 | Rotator |

## RagDollDeathAnimAssetInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DeathAnim | 0x0 | 8 | AnimSequence |
| Variants | 0x8 | 16 |  |

## RagDollDeathAnimAssets

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DefalutDeathAnim | 0x0 | 8 | AnimSequence |
| DefalutDeathDelayTime | 0x8 | 4 | RagDollDeathAnimAssets |
| StandLeftRightRangeAngle | 0xc | 4 | RagDollDeathAnimVariant |
| StandDeaths | 0x10 | 16 |  |
| StandLeftShoulderDeaths | 0x20 | 16 |  |
| StandRightShoulderDeaths | 0x30 | 16 |  |
| StandLeftLegDeaths | 0x40 | 16 |  |
| StandRightLegDeaths | 0x50 | 16 |  |
| StandHeadDeaths | 0x60 | 16 |  |
| StandLegDeaths | 0x70 | 16 |  |
| StandBodyFLDeath | 0x80 | 24 | RagDollDeathAnimAssetInfo |
| StandBodyFRDeath | 0x98 | 24 | RagDollDeathAnimAssetInfo |
| StandLegFLDeath | 0xb0 | 24 | RagDollDeathAnimAssetInfo |
| StandLegFRDeath | 0xc8 | 24 | RagDollDeathAnimAssetInfo |
| StandHeadHeavyDeath | 0xe0 | 24 | RagDollDeathAnimAssetInfo |
| StandBodyFHeavyDeath | 0xf8 | 24 | RagDollDeathAnimAssetInfo |
| StandBodyFLHeavyDeath | 0x110 | 24 | RagDollDeathAnimAssetInfo |
| StandBodyFRHeavyDeath | 0x128 | 24 | RagDollDeathAnimAssetInfo |
| CrouchDeaths | 0x140 | 16 |  |
| ProneDeaths | 0x150 | 16 |  |
| SwimDeaths | 0x160 | 16 |  |
| ImpendingDeaths | 0x170 | 16 |  |
| PaasageDeaths | 0x180 | 16 |  |
| DriverDeaths | 0x190 | 16 |  |
| ParachuteDeaths | 0x1a0 | 16 |  |

## RagDollDeathAnimVariant

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DeathAnim | 0x0 | 8 | AnimSequence |
| Weight | 0x8 | 4 | RagDollDeathConfigTable |

## RagDollDeathConfigTable

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ServerRagdollPhysicsAsset | 0x10 | 8 | PhysicsAsset |
| ClientRagDollPhysicsAsset | 0x18 | 8 | PhysicsAsset |
| PhysicalAnimationName | 0x20 | 8 | RagDollDeathConfigTable |
| DeathAnimationFourDirTolerantAngle | 0x28 | 4 | RagDollDeathConfigTable |
| DeathMaxSpeedFromAnimation | 0x2c | 4 | RagDollDeathConfigTable |
| DeathPhysicStrength | 0x30 | 4 | RagDollDeathConfigTable |
| DeathPhysicServerStrength | 0x34 | 4 | RagDollDeathConfigTable |
| DeathCrouchForceStrengthMul | 0x38 | 4 | RagDollDeathForceInfo |
| DeathForceArray | 0x40 | 16 |  |
| ConstraintInfos | 0x50 | 16 |  |
| ConstraintAnimTime | 0x60 | 4 |  |
| bEnableSelfCollision | 0x64 | 1 |  |
| IncreaseDampingBones | 0x68 | 16 |  |
| bEnableHipsConstraint | 0x78 | 1 |  |
| HipsConstraintStiffness | 0x7c | 4 | RagDollDeathConfigTable |
| HipsConstraintDamping | 0x80 | 4 | RagDollDeathConfigTable |
| VehicleVelocityFactor | 0x84 | 4 | RagDollDeathConfigTable |
| VehicleVerticalVelocity | 0x88 | 4 |  |
| RagdollImpulseValue | 0x90 | 80 |  |
| WeaponDeathKnockbacks | 0xe0 | 16 |  |
| BodyDistCheckMap | 0xf0 | 80 |  |
| CapsuleProxyMaterial | 0x140 | 8 | PhysicalMaterial |
| bUseDeathAnimDataAsset | 0x148 | 1 |  |
| DeathAnimDataAsset | 0x150 | 8 | GPRagDollDeathAnimDataAsset |

## RagDollDeathForceInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PlayAnimationTime | 0x0 | 4 | RagDollDeathForceInfo |
| PhysicalAnimationTimer | 0x4 | 4 | RagDollDeathForceInfo |
| BlendToPhysicsTime | 0x8 | 4 |  |
| BoneNameList | 0x10 | 16 |  |
| AddForceBoneNameList | 0x20 | 16 |  |
| HitForceList | 0x30 | 16 |  |
| PartType | 0x40 | 1 | EHitPartType |

## RagDollReplicateData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bIsStopPhysicsFromServer | 0x0 | 1 |  |
| RagDollStopLocationValid | 0x1 | 1 |  |
| bRagdollOnMovableBase | 0x2 | 1 |  |
| bRepMovementValid | 0x3 | 1 |  |
| RagDollStopLocation | 0x4 | 12 | Vector |
| ReplicatePhysicsMovement | 0x10 | 56 | RepMovement |
| MeshOffsetZ | 0x48 | 4 | RagDollDeathAnimAssets |
| bRagdollErrorNeedClear | 0x4c | 1 |  |

## RandomStream

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InitialSeed | 0x0 | 4 | RandomStream |
| Seed | 0x4 | 4 | InterpCurveLinearColor |

## RawDistribution

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Table | 0x0 | 32 | DistributionLookupTable |

## RawDistributionFloat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MinValue | 0x20 | 4 | RawDistributionFloat |
| MaxValue | 0x24 | 4 | DirectionalShadowUseSkylightAOParameters |
| Distribution | 0x28 | 8 | DistributionFloat |

## RawDistributionVector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MinValue | 0x20 | 4 | RawDistributionVector |
| MaxValue | 0x24 | 4 | RawDistributionFloat |
| MinValueVec | 0x28 | 12 | Vector |
| MaxValueVec | 0x34 | 12 | Vector |
| Distribution | 0x40 | 8 | DistributionVector |

## RealCurve

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DefaultValue | 0x68 | 4 | SmokeBlindnessVolumeConfig |
| PreInfinityExtrap | 0x6c | 1 | ERichCurveExtrapolation |
| PostInfinityExtrap | 0x6d | 1 | ERichCurveExtrapolation |

## RepAttachment

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AttachParent | 0x0 | 8 | Actor |
| LocationOffset | 0x8 | 12 | Vector_NetQuantize100 |
| RelativeScale3D | 0x14 | 12 | Vector_NetQuantize100 |
| RotationOffset | 0x20 | 12 | Rotator |
| AttachSocket | 0x2c | 8 | Actor |
| AttachComponent | 0x38 | 8 | SceneComponent |

## RepMovement

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LinearVelocity | 0x0 | 12 | Vector |
| AngularVelocity | 0xc | 12 | Vector |
| Location | 0x18 | 16 | EncVector |
| Rotation | 0x28 | 12 | Rotator |
| bSimulatedPhysicSleep | 0x34 | 1 |  |
| bRepPhysics | 0x34 | 1 |  |
| LocationQuantizationLevel | 0x35 | 1 | EVectorQuantization |
| VelocityQuantizationLevel | 0x36 | 1 | EVectorQuantization |
| RotationQuantizationLevel | 0x37 | 1 | ERotatorQuantization |

## RepOverrideMovementInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EnableOverrideSpeedPose | 0x0 | 1 |  |
| CurrentOverridePose | 0x1 | 1 | EOverrideMovementType |

## RepRootMotionMontage

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bIsActive | 0x0 | 1 |  |
| AnimMontage | 0x8 | 8 | AnimMontage |
| Position | 0x10 | 4 | RepRootMotionMontage |
| Location | 0x14 | 12 | Vector_NetQuantize100 |
| Rotation | 0x20 | 12 | Rotator |
| MovementBase | 0x30 | 8 | PrimitiveComponent |
| MovementBaseBoneName | 0x38 | 8 |  |
| bRelativePosition | 0x40 | 1 |  |
| bRelativeRotation | 0x41 | 1 |  |
| AuthoritativeRootMotion | 0x48 | 248 | RootMotionSourceGroup |
| Acceleration | 0x140 | 12 | Vector_NetQuantize10 |
| LinearVelocity | 0x14c | 12 | Vector_NetQuantize10 |

## ReplifetimeCond

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PropertyName | 0x0 | 16 | ParamSplinePointParameter |
| Cond | 0x10 | 1 | ELifetimeCondition |

## RescueCascadeParamInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DetectShowWhiteDotMinRadius | 0x0 | 4 | RescueCascadeParamInfo |
| DetectShowWhiteDotMaxRadius | 0x4 | 4 | RescueCascadeParamInfo |
| DetectShowHUDMinRadius | 0x8 | 4 | RescueCascadeParamInfo |
| DetectShowHUDMaxRadius | 0xc | 4 | RescueCascadeParamInfo |
| DetectShowHUDHorizontalAngle | 0x10 | 4 | RescueCascadeParamInfo |
| DetectShowHUDVerticalAngle | 0x14 | 4 | RescueCascadeParamInfo |
| DetectShowZRangeMax | 0x18 | 4 | InventoryPickup_DeadBody |

## ReverbSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bApplyReverb | 0x0 | 1 |  |
| ReverbEffect | 0x8 | 8 | ReverbEffect |
| ReverbPluginEffect | 0x10 | 8 | SoundEffectSubmixPreset |
| Volume | 0x18 | 4 | ReverbSettings |
| FadeTime | 0x1c | 4 | InteriorSettings |

## RichCurve

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Keys | 0x70 | 16 |  |
| Orders | 0x80 | 16 |  |

## RigTransformConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TranformType | 0x0 | 1 | EConstraintTransform |
| ParentSpace | 0x4 | 8 | RigTransformConstraint |
| Weight | 0xc | 4 | SCSBResult |

## RigidBodyContactInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ContactPosition | 0x0 | 12 | Vector |
| ContactNormal | 0xc | 12 | Vector |
| ContactPenetration | 0x18 | 4 | LightmassDirectionalLightSettings |
| PhysMaterial | 0x20 | 8 | PhysicalMaterial |

## RigidBodyErrorCorrection

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PingExtrapolation | 0x0 | 4 | RigidBodyErrorCorrection |
| PingLimit | 0x4 | 4 | RigidBodyErrorCorrection |
| ErrorPerLinearDifference | 0x8 | 4 | RigidBodyErrorCorrection |
| ErrorPerAngularDifference | 0xc | 4 | RigidBodyErrorCorrection |
| MaxRestoredStateError | 0x10 | 4 | RigidBodyErrorCorrection |
| MaxLinearHardSnapDistance | 0x14 | 4 | RigidBodyErrorCorrection |
| PositionLerp | 0x18 | 4 | RigidBodyErrorCorrection |
| AngleLerp | 0x1c | 4 | RigidBodyErrorCorrection |
| LinearVelocityCoefficient | 0x20 | 4 | RigidBodyErrorCorrection |
| AngularVelocityCoefficient | 0x24 | 4 | RigidBodyErrorCorrection |
| ErrorAccumulationSeconds | 0x28 | 4 | RigidBodyErrorCorrection |
| ErrorAccumulationDistanceSq | 0x2c | 4 | RigidBodyErrorCorrection |
| ErrorAccumulationSimilarity | 0x30 | 4 | RigidBodyContactInfo |

## RootMotionActionInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bAbortPlayingAnim | 0x0 | 1 |  |
| AnimInfo | 0x10 | 208 | AnimRootMotionInfo |
| Time | 0xe0 | 4 | RootMotionActionInfo |
| IsPlanningMotion | 0xe4 | 1 |  |
| PlanningFrameNumber | 0xe8 | 4 | PlanningTransitionInfo |

## RootMotionFinishVelocitySettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Mode | 0x0 | 1 | ERootMotionFinishVelocityMode |
| SetVelocity | 0x4 | 12 | Vector |
| ClampVelocity | 0x10 | 4 | Node |

## RootMotionMovementParams

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bHasRootMotion | 0x0 | 1 |  |
| BlendWeight | 0x4 | 4 | SimulatedRootMotionReplicatedMove |
| RootMotionTransform | 0x10 | 48 | Transform |

## RootMotionSource

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Priority | 0x8 | 2 | RootMotionSource |
| LocalID | 0xa | 2 | RootMotionSource |
| AccumulateMode | 0xc | 1 | ERootMotionAccumulateMode |
| InstanceName | 0x10 | 8 | ClothPhysicsProperties_Legacy |
| StartTime | 0x18 | 4 | RootMotionSource |
| CurrentTime | 0x1c | 4 | RootMotionSource |
| PreviousTime | 0x20 | 4 | RootMotionSource |
| duration | 0x24 | 4 | RootMotionFinishVelocitySettings |
| Status | 0x28 | 1 | RootMotionSourceStatus |
| Settings | 0x29 | 1 | RootMotionSourceSettings |
| bInLocalSpace | 0x2a | 1 |  |
| RootMotionParams | 0x30 | 64 | RootMotionMovementParams |
| FinishVelocityParams | 0x70 | 20 | RootMotionFinishVelocitySettings |

## RootMotionSourceGroup

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bHasAdditiveSources | 0xe8 | 1 |  |
| bHasOverrideSources | 0xe8 | 1 |  |
| bIsAdditiveVelocityApplied | 0xe8 | 1 |  |
| LastAccumulatedSettings | 0xe9 | 1 | RootMotionSourceSettings |
| LastPreAdditiveVelocity | 0xec | 12 | Vector_NetQuantize10 |

## RootMotionSourceSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Flags | 0x0 | 1 |  |

## RootMotionSourceStatus

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Flags | 0x0 | 1 |  |

## RootMotionSource_JumpForce

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Rotation | 0x84 | 12 | Rotator |
| Distance | 0x90 | 4 | RootMotionSource_JumpForce |
| height | 0x94 | 4 | RootMotionSource |
| bDisableTimeout | 0x98 | 1 |  |
| PathOffsetCurve | 0xa0 | 8 | CurveVector |
| TimeMappingCurve | 0xa8 | 8 | CurveFloat |

## RootMotionSource_RadialForce

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x84 | 12 | Vector |
| LocationActor | 0x90 | 8 | Actor |
| radius | 0x98 | 4 | RootMotionSource_RadialForce |
| Strength | 0x9c | 4 | RootMotionSource_JumpForce |
| bIsPush | 0xa0 | 1 |  |
| bNoZForce | 0xa1 | 1 |  |
| StrengthDistanceFalloff | 0xa8 | 8 | CurveFloat |
| StrengthOverTime | 0xb0 | 8 | CurveFloat |
| bUseFixedWorldDirection | 0xb8 | 1 |  |
| FixedWorldDirection | 0xbc | 12 | Rotator |

## Rotator

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| pitch | 0x0 | 4 | Rotator |
| Yaw | 0x4 | 4 | Rotator |
| Roll | 0x8 | 4 | Plane |

## RuntimeCurveLinearColor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ColorCurves | 0x0 | 152 | RichCurve |
| ExternalCurve | 0x260 | 8 | CurveLinearColor |

## RuntimeFloatCurve

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| EditorCurveData | 0x0 | 152 | RichCurve |
| ExternalCurve | 0x98 | 8 | CurveFloat |

## SCSBResult

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| M | 0x0 | 4 | SpriteCategoryInfo |

## SMExposedFunctionHandler

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BoundFunction | 0x0 | 8 | SMGraphProperty_Base |
| Function | 0x8 | 8 | Function |

## SMGraphProperty_Base

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| GraphEvaluator | 0x8 | 32 | SMExposedFunctionHandler |
| VariableName | 0x30 | 8 | EdGraphPinType |
| VariableType | 0x38 | 88 | EdGraphPinType |
| MemberReference | 0x90 | 56 | MemberReference |
| bIsInArray | 0xc8 | 1 |  |
| Guid | 0xcc | 16 | Guid |
| GuidUnmodified | 0xdc | 16 | Guid |
| OwnerGuid | 0xec | 16 | Guid |
| TemplateGuid | 0xfc | 16 | Guid |
| GuidIndex | 0x10c | 4 | LuaFileTag |

## SOLCharacter

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FootballSignTag | 0x3c64 | 8 | GameplayTag |
| FootballSignParamInfo_HD | 0x3c6c | 28 | RescueCascadeParamInfo |
| FootballSignParamInfo_Mobile | 0x3c88 | 28 | RescueCascadeParamInfo |
| HoldPokerCardUrgeTag | 0x3ca4 | 8 | GameplayTag |
| HoldPokerCardUrgeParamInfo_HD | 0x3cac | 28 | RescueCascadeParamInfo |
| HoldPokerCardUrgeParamInfo_Mobile | 0x3cc8 | 28 | RescueCascadeParamInfo |
| FishingComponent | 0x3ce8 | 8 | SOLFishingComponent |
| bSoloCinematicMode | 0x3cf0 | 1 |  |
| InstallSkillID | 0x3d48 | 4 | SOLCharacter |
| InstallConfigs | 0x3d50 | 16 |  |
| InstallItemID | 0x3d60 | 4 |  |

## SOLCharacterBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ExplodeDamageDistancePriority | 0x3bc8 | 80 |  |
| DFMExpDataComp | 0x3c18 | 8 | DFMExpDataComponent |
| PlayerExitComponent | 0x3c20 | 8 | PlayerExitComponent |
| RoleLoadComponent | 0x3c28 | 8 | RoleLoadComponent |
| SOLHealthDataComponent | 0x3c30 | 8 | SOLHealthDataComponent |
| CurrencyInGameComponent | 0x3c38 | 8 | SOLCurrencyInGameComponent |
| HidingBodyComponent | 0x3c40 | 8 | DFMHidingBodyComponent |
| ManholeCoverTriggerComponent | 0x3c48 | 8 | DFMManholeCoverTriggerComponent |
| SOLVoiceOverComponent | 0x3c50 | 8 | SOLVoiceOverComponent |
| SOLAerialWorkPlatformCheckComponent | 0x3c58 | 8 | SOLAerialWorkPlatformCheckComponent |
| bEnableSignificance | 0x3c60 | 1 |  |

## SOLExitConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PlayerExitId | 0x10 | 4 | SOLExitConfig |
| MapID | 0x14 | 4 | SOLExitConfig |
| PlayerExitName | 0x18 | 24 | MapGlitchEffectConfigRow |

## SVTIntVector4

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | SVTIntVector4 |
| Y | 0x4 | 4 | SVTIntVector4 |
| Z | 0x8 | 4 | SVTIntVector4 |
| W | 0xc | 4 | SkeletalMaterial |

## SafeHousePlayerController

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DefaultCharacterClass | 0xd90 | 8 | Class |
| DefaultRangeCharacterClass | 0xd98 | 8 | Class |
| HUDModeMapping | 0xda0 | 80 |  |
| bKeepLastHUD | 0xdf0 | 1 |  |
| CurrentHUDMode | 0xdf1 | 1 | ESafeHouseHUDMode |
| OnPreload3DSafeHouseDone | 0xdf4 | 16 |  |
| OnSafeHouseHUDAutoReleased | 0xe08 | 16 |  |
| bHasSpawnCharacter | 0xe1c | 1 |  |
| SafeHouseCharacter | 0xe28 | 8 | DFMCharacter |
| RangeCharacter | 0xe30 | 8 | DFMCharacter |
| OnLoadOrUnloadCollectionRoomDone | 0xe64 | 16 |  |

## ScalableFloat

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Value | 0x0 | 4 | CurveTableRowHandle |
| Curve | 0x8 | 16 | CurveTableRowHandle |

## SceneComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PhysicsVolume | 0x100 | 8 | PhysicsVolume |
| AttachParent | 0x108 | 8 | SceneComponent |
| AttachSocketName | 0x110 | 8 |  |
| AttachChildren | 0x118 | 16 |  |
| ClientAttachedChildren | 0x128 | 16 |  |
| RelativeLocation | 0x168 | 16 | EncVector |
| RelativeRotation | 0x178 | 12 | Rotator |
| RelativeScale3D | 0x184 | 12 | Vector |
| ComponentVelocity | 0x190 | 12 | Vector |
| bComponentToWorldUpdated | 0x19c | 1 |  |
| bAbsoluteLocation | 0x19c | 1 |  |
| bAbsoluteRotation | 0x19c | 1 |  |
| bAbsoluteScale | 0x19c | 1 |  |
| bVisible | 0x19c | 1 |  |
| bHiddenInGame | 0x19c | 1 |  |
| bSkipUpdateTransformsWhenHidden | 0x19c | 1 |  |
| bShouldBeAttached | 0x19d | 1 |  |
| bShouldSnapLocationWhenAttached | 0x19d | 1 |  |
| bShouldSnapRotationWhenAttached | 0x19d | 1 |  |
| bShouldUpdatePhysicsVolume | 0x19d | 1 |  |
| bBoundsChangeTriggersStreamingDataRebuild | 0x19d | 1 |  |
| bUseAttachParentBound | 0x19d | 1 |  |
| Mobility | 0x19f | 1 | EComponentMobility |
| DetailMode | 0x1a0 | 1 | EDetailMode |
| PhysicsVolumeChangedDelegate | 0x1a1 | 1 |  |

## SceneComponentInstanceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AttachedInstanceComponents | 0x58 | 80 |  |

## SceneWeaponInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DSWorldLoc | 0x0 | 12 | Vector |
| WeaponType | 0xc | 1 | ESceneWeaponType |
| HealthState | 0xd | 1 | ESceneHealthState |
| CampId | 0x10 | 4 | SceneWeaponInfo |
| TeamID | 0x14 | 4 |  |
| MarkedCampIDArray | 0x18 | 16 |  |
| bIsTeamleader | 0x28 | 1 |  |
| bIsCommander | 0x29 | 1 |  |
| PlayerId | 0x2c | 4 | VehicleInfo |

## ScreenMessageString

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Key | 0x0 | 8 | ScreenMessageString |
| ScreenMessage | 0x8 | 16 | ScreenMessageString |
| DisplayColor | 0x18 | 4 | Color |
| TimeToDisplay | 0x1c | 4 | ScreenMessageString |
| CurrentTimeDisplayed | 0x20 | 4 | GameNameRedirect |
| TextScale | 0x24 | 8 | Vector2D |

## SeriesStyleManualMapping

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SeriesId | 0x0 | 8 | KantanSeriesStyle |
| Style | 0x8 | 32 | KantanSeriesStyle |

## ServerBouncePingParams

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TC1 | 0x0 | 8 | ClientPingInfo |
| ClientPingInfo | 0x8 | 20 | ClientPingInfo |

## SimpleCurveKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Time | 0x0 | 4 | SimpleCurveKey |
| Value | 0x4 | 4 |  |

## SimpleMemberReference

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MemberParent | 0x0 | 8 | Object |
| MemberName | 0x8 | 8 |  |
| MemberGuid | 0x10 | 16 | Guid |

## SimpleMinimalViewInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Location | 0x0 | 12 | Vector |
| Rotation | 0xc | 12 | Rotator |
| FOV | 0x18 | 4 | SimpleMinimalViewInfo |
| DesiredFOV | 0x1c | 4 | SimpleMinimalViewInfo |
| OrthoWidth | 0x20 | 4 | SimpleMinimalViewInfo |
| OrthoNearClipPlane | 0x24 | 4 | SimpleMinimalViewInfo |
| OrthoFarClipPlane | 0x28 | 4 | SimpleMinimalViewInfo |
| AspectRatio | 0x2c | 4 | SimpleMinimalViewInfo |
| bConstrainAspectRatio | 0x30 | 1 |  |
| bUseFieldOfViewForLOD | 0x30 | 1 |  |
| ProjectionMode | 0x31 | 1 | ECameraProjectionMode |
| PostProcessBlendWeight | 0x34 | 4 | GPPathWayPointPauseSettings |
| OffCenterProjectionOffset | 0x38 | 8 | Vector2D |

## SimulatedRootMotionReplicatedMove

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Time | 0x0 | 4 | RepRootMotionMontage |
| RootMotion | 0x8 | 344 | RepRootMotionMontage |

## SingleAnimationPlayData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AnimToPlay | 0x0 | 8 | AnimationAsset |
| bSavedLooping | 0x8 | 1 |  |
| bSavedPlaying | 0x8 | 1 |  |
| SavedPosition | 0xc | 4 | SingleAnimationPlayData |
| SavedPlayRate | 0x10 | 4 | SimpleCurveKey |

## SkelMeshSkinWeightInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Bones | 0x0 | 4 |  |
| Weights | 0x20 | 1 |  |

## SkeletalMaterial

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MaterialInterface | 0x0 | 8 | MaterialInterface |
| MaterialSlotName | 0x8 | 8 | RootMotionSource_RadialForce |
| UVChannelData | 0x10 | 20 | MeshUVChannelInfo |

## SkeletalMeshBuildSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bRecomputeNormals | 0x0 | 1 |  |
| bRecomputeTangents | 0x0 | 1 |  |
| bUseMikkTSpace | 0x0 | 1 |  |
| bComputeWeightedNormals | 0x0 | 1 |  |
| bRemoveDegenerates | 0x0 | 1 |  |
| bUseHighPrecisionTangentBasis | 0x0 | 1 |  |
| bUseFullPrecisionUVs | 0x0 | 1 |  |
| bBuildAdjacencyBuffer | 0x0 | 1 |  |
| ThresholdPosition | 0x4 | 4 | SkeletalMeshBuildSettings |
| ThresholdTangentNormal | 0x8 | 4 | SkeletalMeshBuildSettings |
| ThresholdUV | 0xc | 4 | MeshNaniteSettings |

## SkeletalMeshComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AnimBlueprintGeneratedClass | 0x978 | 8 | AnimBlueprintGeneratedClass |
| AnimClass | 0x980 | 8 | Class |
| AnimScriptInstance | 0x988 | 8 | AnimInstance |
| PostProcessAnimInstance | 0x990 | 8 | AnimInstance |
| AnimationData | 0x998 | 24 | SingleAnimationPlayData |
| RootBoneTranslation | 0x9c0 | 12 | Vector |
| LineCheckBoundsScale | 0x9cc | 12 | Vector |
| LinkedInstances | 0x9f8 | 16 |  |
| CachedBoneSpaceTransforms | 0xa08 | 16 |  |
| CachedComponentSpaceTransforms | 0xa18 | 16 |  |
| GlobalAnimRateScale | 0xa48 | 4 | SkeletalMeshComponent |
| KinematicBonesUpdateType | 0xa4c | 1 | EKinematicBonesUpdateToPhysics |
| PhysicsTransformUpdateMode | 0xa4d | 1 | EPhysicsTransformUpdateMode |
| AnimationMode | 0xa4f | 1 | EAnimationMode |
| bDisablePostProcessBlueprint | 0xa51 | 1 |  |
| bUpdateOverlapsOnAnimationFinalize | 0xa51 | 1 |  |
| bHasValidBodies | 0xa51 | 1 |  |
| bBlendPhysics | 0xa51 | 1 |  |
| bEnableAnimInstanceSkeletalCompatibleCheck | 0xa51 | 1 |  |
| bEnablePhysicsOnDedicatedServer | 0xa52 | 1 |  |
| bUpdateJointsFromAnimation | 0xa52 | 1 |  |
| bDisableClothSimulation | 0xa52 | 1 |  |
| bAllowAnimCurveEvaluation | 0xa52 | 1 |  |
| bDisableAnimCurves | 0xa52 | 1 |  |
| bCollideWithEnvironment | 0xa53 | 1 |  |
| bCollideWithAttachedChildren | 0xa53 | 1 |  |
| bLocalSpaceSimulation | 0xa53 | 1 |  |
| bResetAfterTeleport | 0xa53 | 1 |  |
| bDeferKinematicBoneUpdate | 0xa53 | 1 |  |
| bNoSkeletonUpdate | 0xa53 | 1 |  |
| bPauseAnims | 0xa53 | 1 |  |
| bUseRefPoseOnInitAnim | 0xa54 | 1 |  |
| bEnablePerPolyCollision | 0xa54 | 1 |  |
| bForceRefpose | 0xa54 | 1 |  |
| bOnlyAllowAutonomousTickPose | 0xa54 | 1 |  |
| bIsAutonomousTickPose | 0xa54 | 1 |  |
| bOldForceRefPose | 0xa54 | 1 |  |
| bShowPrePhysBones | 0xa54 | 1 |  |
| bRequiredBonesUpToDate | 0xa54 | 1 |  |
| bAnimTreeInitialised | 0xa55 | 1 |  |
| bIncludeComponentLocationIntoBounds | 0xa55 | 1 |  |
| bEnableLineCheckWithBounds | 0xa55 | 1 |  |
| bUseBendingElements | 0xa55 | 1 |  |
| bUseTetrahedralConstraints | 0xa55 | 1 |  |
| bUseThinShellVolumeConstraints | 0xa55 | 1 |  |
| bUseSelfCollisions | 0xa55 | 1 |  |
| bUseContinuousCollisionDetection | 0xa55 | 1 |  |
| bPropagateCurvesToSlaves | 0xa56 | 1 |  |
| bSkipKinematicUpdateWhenInterpolating | 0xa56 | 1 |  |
| bSkipBoundsUpdateWhenInterpolating | 0xa56 | 1 |  |
| bAggregateSelfCollision | 0xa56 | 1 |  |
| bShouldTickAnimationDuringInitAnim | 0xa56 | 1 |  |
| LastPoseTickFrame | 0xa58 | 4 | SkeletalMeshComponent |
| bNeedsQueuedAnimEventsDispatched | 0xa5c | 1 |  |
| CachedAnimCurveUidVersion | 0xa5e | 2 | SkeletalMeshComponent |
| MassMode | 0xa60 | 1 | EClothMassMode |
| UniformMass | 0xa64 | 4 | SkeletalMeshComponent |
| TotalMass | 0xa68 | 4 | SkeletalMeshComponent |
| Density | 0xa6c | 4 | SkeletalMeshComponent |
| MinPerParticleMass | 0xa70 | 4 | SkeletalMeshComponent |
| ClothBlendWeight | 0xa74 | 4 | SkeletalMeshComponent |
| EdgeStiffness | 0xa78 | 4 | SkeletalMeshComponent |
| BendingStiffness | 0xa7c | 4 | SkeletalMeshComponent |
| AreaStiffness | 0xa80 | 4 | SkeletalMeshComponent |
| VolumeStiffness | 0xa84 | 4 | TestConfigSkill |
| StrainLimitingStiffness | 0xa88 | 4 | SkeletalMeshComponent |
| ShapeTargetStiffness | 0xa8c | 4 |  |
| DisallowedAnimCurves | 0xa90 | 16 |  |
| BodySetup | 0xaa0 | 8 | BodySetup |
| OnConstraintBroken | 0xab0 | 16 |  |
| ClothingSimulationFactory | 0xac0 | 8 | Class |
| TeleportDistanceThreshold | 0xbd0 | 4 | SkeletalMeshComponent |
| TeleportRotationThreshold | 0xbd4 | 4 |  |
| ClothingInteractor | 0xc30 | 8 | ClothingSimulationInteractor |
| OnAnimInitialized | 0xd00 | 16 |  |
| bDoUseBatchUpdate | 0xf39 | 1 |  |
| bForceUseParallelAnimEvaluation | 0xf3a | 1 |  |
| bOverrideCullScreenSize | 0xf70 | 1 |  |

## SkinWeightProfileInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Name | 0x0 | 8 | SkelMeshSkinWeightInfo |
| DefaultProfile | 0x8 | 1 | PerPlatformBool |
| DefaultProfileFromLODIndex | 0xc | 4 | PerPlatformInt |

## SkinnedMeshComponent

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SkeletalMesh | 0x718 | 8 | SkeletalMesh |
| EfffectPassMaterial | 0x720 | 8 | MaterialInterface |
| bDrawEffectPass | 0x728 | 1 |  |
| bReverseDrawEffectPassCulling | 0x728 | 1 |  |
| bEffectPassNeedDepth | 0x728 | 1 |  |
| bDrawSecondPassMaterial | 0x728 | 1 |  |
| SecondPassMaterials | 0x730 | 16 |  |
| MasterPoseComponent | 0x744 | 8 | SkinnedMeshComponent |
| PhysicsAssetOverride | 0x848 | 8 | PhysicsAsset |
| ForcedLodModel | 0x850 | 4 | SkinnedMeshComponent |
| MinLodModel | 0x854 | 4 | SkinnedMeshComponent |
| StreamingDistanceMultiplier | 0x868 | 4 | SkeletalMeshComponent |
| MinURO | 0x86c | 4 | SkinnedMeshComponent |
| ExplicitlyURO | 0x870 | 4 | SkinnedMeshComponent |
| ExplicitlyRate | 0x874 | 4 | SkinnedMeshComponent |
| LODInfo | 0x880 | 16 |  |
| VisibilityBasedAnimTickOption | 0x8b4 | 1 | EVisibilityBasedAnimTickOption |
| bServerOnlyTickMontage | 0x8b6 | 1 |  |
| bOverrideMinLOD | 0x8b6 | 1 |  |
| bUseBoundsFromMasterPoseComponent | 0x8b6 | 1 |  |
| bForceWireframe | 0x8b6 | 1 |  |
| bDisplayBones | 0x8b6 | 1 |  |
| bDisableMorphTarget | 0x8b6 | 1 |  |
| bHideSkin | 0x8b7 | 1 |  |
| bPerBoneMotionBlur | 0x8b7 | 1 |  |
| bComponentUseFixedSkelBounds | 0x8b7 | 1 |  |
| bConsiderAllBodiesForBounds | 0x8b7 | 1 |  |
| bConsiderValidBodiesForBounds | 0x8b7 | 1 |  |
| bSyncAttachParentLOD | 0x8b7 | 1 |  |
| bCanHighlightSelectedSections | 0x8b7 | 1 |  |
| bRecentlyRendered | 0x8b7 | 1 |  |
| bRecentlyRenderedOnScreen | 0x8b8 | 1 |  |
| bCastCapsuleDirectShadow | 0x8b8 | 1 |  |
| bCastCapsuleIndirectShadow | 0x8b8 | 1 |  |
| bCPUSkinning | 0x8b8 | 1 |  |
| bEnableUpdateRateOptimizations | 0x8b8 | 1 |  |
| bDisplayDebugUpdateRateOptimizations | 0x8b8 | 1 |  |
| bForceDynamicforShadowcache | 0x8b9 | 1 |  |
| bEnableUpdateShadowCacheState | 0x8ba | 1 |  |
| ShadowLODOffset | 0x8bc | 4 | SkinnedMeshComponent |
| bRenderStatic | 0x8c0 | 1 |  |
| bIgnoreMasterPoseComponentLOD | 0x8c0 | 1 |  |
| bForceTranslucentReceiveCSM | 0x8c0 | 1 |  |
| bCachedLocalBoundsUpToDate | 0x8c0 | 1 |  |
| bForceMeshObjectUpdate | 0x8c0 | 1 |  |
| CapsuleIndirectShadowMinVisibility | 0x8c4 | 4 |  |
| CachedWorldSpaceBounds | 0x8e8 | 28 | BoxSphereBounds |
| CachedWorldToLocalTransform | 0x910 | 64 | Matrix |

## SlateBrush

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| imageSize | 0x8 | 8 | Vector2D |
| Margin | 0x10 | 16 | Margin |
| TintColor | 0x20 | 40 | SlateColor |
| ResourceObject | 0x48 | 8 | Object |
| ResourceName | 0x50 | 8 |  |
| UVRegion | 0x58 | 20 | Box2D |
| DrawAs | 0x6c | 1 | ESlateBrushDrawType |
| Tiling | 0x6d | 1 | ESlateBrushTileType |
| Mirroring | 0x6e | 1 | ESlateBrushMirrorType |
| ImageType | 0x6f | 1 | ESlateBrushImageType |
| bAdaptiveTiling | 0x70 | 1 |  |
| bIsDynamicallyLoaded | 0x88 | 1 |  |
| bHasUObject | 0x88 | 1 |  |

## SlateColor

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SpecifiedColor | 0x0 | 16 | LinearColor |
| ColorUseRule | 0x10 | 1 | ESlateColorStylingMode |

## SmokeBlindnessVolumeConfig

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SmokeVisibleDistance | 0x0 | 4 |  |

## SoftClassPath

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## SoftObjectPath

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| AssetPathName | 0x0 | 8 | SoftObjectPath |
| SubPathString | 0x8 | 16 | timecode |

## SoundAttenuationPluginSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SpatializationPluginSettingsArray | 0x0 | 16 |  |
| OcclusionPluginSettingsArray | 0x10 | 16 |  |
| ReverbPluginSettingsArray | 0x20 | 16 |  |

## SoundAttenuationSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bAttenuate | 0xc8 | 1 |  |
| bSpatialize | 0xc8 | 1 |  |
| bAttenuateWithLPF | 0xc8 | 1 |  |
| bEnableListenerFocus | 0xc8 | 1 |  |
| bEnableFocusInterpolation | 0xc8 | 1 |  |
| bEnableOcclusion | 0xc8 | 1 |  |
| bUseComplexCollisionForOcclusion | 0xc8 | 1 |  |
| bEnableReverbSend | 0xc8 | 1 |  |
| bApplyNormalizationToStereoSounds | 0xc9 | 1 |  |
| bEnableLogFrequencyScaling | 0xc9 | 1 |  |
| SpatializationAlgorithm | 0xca | 1 | ESoundSpatializationAlgorithm |
| BinauralRadius | 0xcc | 4 | SoundAttenuationSettings |
| AbsorptionMethod | 0xd0 | 1 | EAirAbsorptionMethod |
| OcclusionTraceChannel | 0xd1 | 1 | ECollisionChannel |
| ReverbSendMethod | 0xd2 | 1 | EReverbSendMethod |
| OmniRadius | 0xd4 | 4 | SoundAttenuationSettings |
| StereoSpread | 0xd8 | 4 | SoundAttenuationSettings |
| LPFRadiusMin | 0xdc | 4 | SoundAttenuationSettings |
| LPFRadiusMax | 0xe0 | 4 | SoundAttenuationSettings |
| CustomLowpassAirAbsorptionCurve | 0xe8 | 160 | RuntimeFloatCurve |
| CustomHighpassAirAbsorptionCurve | 0x188 | 160 | RuntimeFloatCurve |
| LPFFrequencyAtMin | 0x228 | 4 | SoundAttenuationSettings |
| LPFFrequencyAtMax | 0x22c | 4 | SoundAttenuationSettings |
| HPFFrequencyAtMin | 0x230 | 4 | SoundAttenuationSettings |
| HPFFrequencyAtMax | 0x234 | 4 | SoundAttenuationSettings |
| FocusAzimuth | 0x238 | 4 | SoundAttenuationSettings |
| NonFocusAzimuth | 0x23c | 4 | SoundAttenuationSettings |
| FocusDistanceScale | 0x240 | 4 | SoundAttenuationSettings |
| NonFocusDistanceScale | 0x244 | 4 | SoundAttenuationSettings |
| FocusPriorityScale | 0x248 | 4 | SoundAttenuationSettings |
| NonFocusPriorityScale | 0x24c | 4 | SoundAttenuationSettings |
| FocusVolumeAttenuation | 0x250 | 4 | SoundAttenuationSettings |
| NonFocusVolumeAttenuation | 0x254 | 4 | SoundAttenuationSettings |
| FocusAttackInterpSpeed | 0x258 | 4 | SoundAttenuationSettings |
| FocusReleaseInterpSpeed | 0x25c | 4 | SoundSourceBusSendInfo |
| OcclusionLowPassFilterFrequency | 0x260 | 4 | SoundAttenuationSettings |
| OcclusionVolumeAttenuation | 0x264 | 4 | SoundAttenuationSettings |
| OcclusionInterpolationTime | 0x268 | 4 | SoundAttenuationSettings |
| ReverbWetLevelMin | 0x26c | 4 | SoundAttenuationSettings |
| ReverbWetLevelMax | 0x270 | 4 | SoundAttenuationSettings |
| ReverbDistanceMin | 0x274 | 4 | SoundAttenuationSettings |
| ReverbDistanceMax | 0x278 | 4 | SoundAttenuationSettings |
| ManualReverbSendLevel | 0x27c | 4 | PrecomputedSkyLightInstanceData |
| CustomReverbSendCurve | 0x280 | 160 | RuntimeFloatCurve |
| PluginSettings | 0x320 | 48 | SoundAttenuationPluginSettings |

## SoundClassAdjuster

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SoundClassObject | 0x0 | 8 | SoundClass |
| VolumeAdjuster | 0x8 | 4 | SoundClassAdjuster |
| PitchAdjuster | 0xc | 4 | SoundClassAdjuster |
| LowPassFilterFrequency | 0x10 | 4 | SoundClassAdjuster |
| bApplyToChildren | 0x14 | 1 |  |
| VoiceCenterChannelVolumeAdjuster | 0x18 | 4 | SoundGroup |

## SoundClassProperties

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Volume | 0x0 | 4 | SoundClassProperties |
| pitch | 0x4 | 4 | SoundClassProperties |
| LowPassFilterFrequency | 0x8 | 4 | SoundClassProperties |
| StereoBleed | 0xc | 4 | SoundClassProperties |
| LFEBleed | 0x10 | 4 | SoundClassProperties |
| VoiceCenterChannelVolume | 0x14 | 4 | SoundClassProperties |
| RadioFilterVolume | 0x18 | 4 | SoundClassProperties |
| RadioFilterVolumeThreshold | 0x1c | 4 | SoundClassProperties |
| bApplyEffects | 0x20 | 1 |  |
| bAlwaysPlay | 0x20 | 1 |  |
| bIsUISound | 0x20 | 1 |  |
| bIsMusic | 0x20 | 1 |  |
| bReverb | 0x20 | 1 |  |
| Default2DReverbSendAmount | 0x24 | 4 | PassiveSoundMixModifier |
| bCenterChannelOnly | 0x28 | 1 |  |
| bApplyAmbientVolumes | 0x28 | 1 |  |
| OutputTarget | 0x29 | 1 | EAudioOutputTarget |
| LoadingBehavior | 0x2a | 1 | ESoundWaveLoadingBehavior |

## SoundConcurrencySettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| MaxCount | 0x0 | 4 | SoundConcurrencySettings |
| bLimitToOwner | 0x4 | 1 |  |
| ResolutionRule | 0x5 | 1 | EMaxConcurrentResolutionRule |
| VolumeScale | 0x8 | 4 | StaticMeshOptimizationSettings |
| VolumeScaleAttackTime | 0xc | 4 | SoundConcurrencySettings |
| bVolumeScaleCanRelease | 0x10 | 1 |  |
| VolumeScaleReleaseTime | 0x14 | 4 | SoundConcurrencySettings |
| VoiceStealReleaseTime | 0x18 | 4 | SoundClassProperties |

## SoundGroup

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SoundGroup | 0x0 | 1 | ESoundGroup |
| DisplayName | 0x8 | 16 | SoundGroup |
| bAlwaysDecompressOnLoad | 0x18 | 1 |  |
| DecompressedDuration | 0x1c | 4 | SoundConcurrencySettings |

## SoundSourceBusSendInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SourceBusSendLevelControlMethod | 0x0 | 1 | ESourceBusSendLevelControlMethod |
| SoundSourceBus | 0x8 | 8 | SoundSourceBus |
| SendLevel | 0x10 | 4 | SoundSourceBusSendInfo |
| MinSendLevel | 0x14 | 4 | SoundSourceBusSendInfo |
| MaxSendLevel | 0x18 | 4 | TextureLODGroup |
| MinSendDistance | 0x1c | 4 | SoundSourceBusSendInfo |
| MaxSendDistance | 0x20 | 4 | ModulatorContinuousParams |
| CustomSendLevelCurve | 0x28 | 160 | RuntimeFloatCurve |

## SpawnBaseAIInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| NpcTemplateTable | 0x0 | 8 | DataTable |
| npcName | 0x8 | 16 | SpawnBaseAIInfo |
| SpawnLocation | 0x18 | 12 | Vector |
| BatchNum | 0x24 | 4 | SpawnBaseAIInfo |
| Inx | 0x28 | 4 | DFMAICharacter |

## Sphere

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Center | 0x0 | 12 | Vector |
| W | 0xc | 4 | AutomationExecutionEntry |

## SpriteCategoryInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Category | 0x0 | 8 | SpriteCategoryInfo |
| DisplayName | 0x8 | 24 | SpriteCategoryInfo |
| Description | 0x20 | 24 | PrimitiveComponentInstanceData |

## StartStopData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bStoping | 0x20 | 1 |  |
| StopType | 0x21 | 1 |  |
| bStarting | 0x22 | 1 |  |
| bPivot | 0x23 | 1 |  |
| PivotDirection | 0x24 | 1 |  |

## StatColorMapEntry

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| In | 0x0 | 4 | MeshNaniteSettings |
| Out | 0x4 | 4 | Color |

## StatColorMapping

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StatName | 0x0 | 16 | StatColorMapEntry |
| ColorMap | 0x10 | 16 |  |
| DisableBlend | 0x20 | 1 |  |

## StaticMeshOptimizationSettings

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ReductionMethod | 0x0 | 1 | EOptimizationType |
| NumOfTrianglesPercentage | 0x4 | 4 | StaticMeshOptimizationSettings |
| MaxDeviationPercentage | 0x8 | 4 | StreamingRenderAssetPrimitiveInfo |
| WeldingThreshold | 0xc | 4 | StaticMeshOptimizationSettings |
| bRecalcNormals | 0x10 | 1 |  |
| NormalsThreshold | 0x14 | 4 |  |
| SilhouetteImportance | 0x18 | 1 |  |
| TextureImportance | 0x19 | 1 |  |
| ShadingImportance | 0x1a | 1 |  |

## StreamableTextureInstance

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## StreamingRenderAssetPrimitiveInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| RenderAsset | 0x0 | 8 | StreamableRenderAsset |
| Bounds | 0x8 | 28 | BoxSphereBounds |
| TexelFactor | 0x24 | 4 | StreamingRenderAssetPrimitiveInfo |
| PackedRelativeBox | 0x28 | 4 | TextureLODGroup |
| bAllowInvalidTexelFactorWhenUnregistered | 0x2c | 1 |  |
| bAffectedByComponentScale | 0x2c | 1 |  |

## StructRedirect

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| OldStructName | 0x0 | 8 | StructRedirect |
| NewStructName | 0x8 | 8 | PluginRedirect |

## TOD_AdditionalPRTMap

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bNeedReloadAdditionalBlockId | 0x0 | 1 |  |
| RuntimeEnableIndex | 0x4 | 4 | TOD_AdditionalPRTMap |
| AdditionalMapDirectory | 0x28 | 16 |  |
| RuntimeAdditionalMapBlockIdToPrefixIndex | 0xa8 | 80 |  |
| AdditionalPRTMarker | 0xf8 | 80 | AdditionalPRTMarker |
| AdditionalTetLightMap | 0x378 | 16 |  |

## TOD_CycleParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| latitude | 0x14 | 4 | TOD_CycleParameters |
| ZRotate | 0x20 | 4 | TOD_PRTPlacingParameters |

## TOD_DayParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LowestSunTime | 0x0 | 4 | TOD_Time |
| MainLightIntensity_Wtx | 0x8 | 160 | RuntimeFloatCurve |
| MainLightColorTint_Wtx | 0xa08 | 616 | RuntimeCurveLinearColor |

## TOD_GiAdjust

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| HackAddFar | 0x10 | 4 | TOD_GiAdjust |
| UseLerp | 0x14 | 1 |  |
| PrtMult | 0x18 | 4 | TOD_GiAdjust |
| PrtMultAverage | 0x1c | 4 | TOD_GiAdjust |
| NormalStrenthen | 0x20 | 4 | TOD_GiAdjust |
| SyncTarget | 0x30 | 24 | SoftObjectPath |
| UseFakeDirectionalBounce | 0x48 | 4 | GPUMeshResourceData |
| GlobalLowQualityMobileBounceColor | 0x4c | 16 | LinearColor |
| GlobalCharacterLightingHack | 0x5c | 16 | LinearColor |
| bEnableBounceReplacing | 0x6c | 1 |  |
| AOReplacingBounceColor | 0x70 | 16 | LinearColor |
| InteriorLightenMinEV | 0x80 | 4 | TOD_GiAdjust |
| InteriorLightenMaxEV | 0x84 | 4 | TOD_GiAdjust |
| MinEVLocalLightScale | 0x88 | 4 | TOD_GiAdjust |
| MaxEVLocalLightScale | 0x8c | 4 | TOD_GiAdjust |
| DynamicObjectLocalLightScale | 0x90 | 4 | TOD_GiAdjust |
| MinWaterSkyvisHD | 0x94 | 4 | TOD_GiAdjust |
| MinWaterSkyLightRGBHD | 0x98 | 16 | LinearColor |
| BakeFullSkyLightIrradiance | 0xa8 | 1 |  |
| bFitAtfIntoWeights | 0xa9 | 1 |  |
| bDisableAlphaTestForPRT | 0xaa | 1 |  |
| bEnableSkylightLeaking | 0xab | 1 |  |
| SkylightLeaking | 0xac | 4 | TOD_GiAdjust |
| FullSkylightLeakingDistance | 0xb0 | 4 | TOD_CycleParameters |
| KeepProbeUnderTerrain | 0xb4 | 1 |  |

## TOD_Names

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| WeatherNames_Wtx | 0x0 | 16 | TOD_AdditionalPRTMap |

## TOD_PRTPlacingParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| VoxelSize | 0x0 | 4 | TOD_PRTPlacingParameters |
| Bandwidth | 0x4 | 4 | TOD_PRTPlacingParameters |
| MaxWidth | 0x8 | 4 | TOD_PRTPlacingParameters |
| MinWidth | 0xc | 4 | TOD_PRTPlacingParameters |
| SmallBoxWidth | 0x10 | 4 | TOD_PRTPlacingParameters |
| SmallBoxWidth_hp | 0x14 | 4 | TOD_PRTPlacingParameters |
| SmallBoxWidth_lw | 0x18 | 4 | TOD_PRTPlacingParameters |
| variance_threshold | 0x1c | 4 | TOD_PRTPlacingParameters |
| krek | 0x20 | 4 | TOD_DayParameters |

## TOD_Sun

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StarDis | 0x18 | 4 | TOD_Sun |
| StarBrightness | 0x1c | 4 | TOD_Sun |
| StarNum | 0x20 | 4 | TOD_Names |
| StarRGB | 0x24 | 16 | LinearColor |

## TOD_Time

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CurrTime | 0x0 | 4 | TOD_Sun |

## TViewTarget

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Target | 0x0 | 8 | Actor |
| POV | 0x10 | 2624 | MinimalViewInfo |
| PlayerState | 0xa50 | 8 | PlayerState |

## TableRowBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## TagContainerAggregator

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| CapturedActorTags | 0x0 | 32 | GameplayTagContainer |
| CapturedSpecTags | 0x20 | 32 | GameplayTagContainer |
| ScopedTags | 0x40 | 32 | GameplayTagContainer |

## TentDistribution

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TipAltitude | 0x0 | 4 | TentDistribution |
| TipValue | 0x4 | 4 | TentDistribution |
| width | 0x8 | 4 | SkinWeightProfileInfo |

## TextSizingParameters

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DrawX | 0x0 | 4 | TextSizingParameters |
| DrawY | 0x4 | 4 | TextSizingParameters |
| DrawXL | 0x8 | 4 | TextSizingParameters |
| DrawYL | 0xc | 4 | WrappedStringElement |
| Scaling | 0x10 | 8 | Vector2D |
| DrawFont | 0x18 | 8 | Font |
| SpacingAdjust | 0x20 | 8 | Vector2D |

## TextureLODGroup

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Group | 0x0 | 1 | TextureGroup |
| LODBias | 0xc | 4 | TextureLODGroup |
| LODBias_Smaller | 0x10 | 4 | TextureLODGroup |
| LODBias_Smallest | 0x14 | 4 | TextureLODGroup |
| NumStreamedMips | 0x1c | 4 | TextureLODGroup |
| MipGenSettings | 0x20 | 1 | TextureMipGenSettings |
| MinLODSize | 0x24 | 4 | TextureLODGroup |
| MaxLODSize | 0x28 | 4 | TextureLODGroup |
| MaxLODSize_Smaller | 0x2c | 4 | TextureLODGroup |
| MaxLODSize_Smallest | 0x30 | 4 | TextureLODGroup |
| OptionalLODBias | 0x34 | 4 | TextureLODGroup |
| OptionalMaxLODSize | 0x38 | 4 | TextureLODGroup |
| MinMagFilter | 0x40 | 8 | TextureLODGroup |
| MipFilter | 0x48 | 8 | TextureLODGroup |
| MipLoadOptions | 0x50 | 1 | ETextureMipLoadOptions |
| DuplicateNonOptionalMips | 0x51 | 1 |  |
| AstcPreferCompressor | 0x52 | 1 | ETextureAstcPreferCompressor |
| LossyCompressionAmount | 0x53 | 1 | ETextureLossyCompressionAmount |
| ScaleRatio | 0x54 | 4 | TextureLODGroup |
| MipsToCook | 0x58 | 4 |  |
| EnableBiasWhenNoStreamable | 0x5c | 4 | TextureOptionalMipsOverride |

## TextureOptionalMipsOverride

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PathPattern | 0x0 | 16 | TextureOptionalMipsOverride |
| NumOptionalMips | 0x10 | 4 |  |

## TickFunction

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TickGroup | 0x8 | 1 | ETickingGroup |
| EndTickGroup | 0x9 | 1 | ETickingGroup |
| bTickEvenWhenPaused | 0xa | 1 |  |
| bCanEverTick | 0xa | 1 |  |
| bStartWithTickEnabled | 0xa | 1 |  |
| bAllowTickOnDedicatedServer | 0xa | 1 |  |
| bEnableLightweightTick | 0xb | 1 |  |
| TickInterval | 0x10 | 4 |  |
| AggregateClass | 0x20 | 8 | Class |
| OwnerLevel | 0x28 | 8 | Level |

## TimerHandle

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Handle | 0x0 | 8 | MaterialInput |

## TireFrictionScalePair

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TireType | 0x0 | 8 | TireType |
| FrictionScale | 0x8 | 4 | PerPlatformString |

## ToggleTrackKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Time | 0x0 | 4 | LightmassMaterialInterfaceSettings |
| ToggleAction | 0x4 | 1 | ETrackToggleAction |

## TrackToSkeletonMap

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BoneTreeIndex | 0x0 | 4 | AnimationTransitionRule |

## Transform

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Rotation | 0x0 | 16 | Quat |
| translation | 0x10 | 12 | Vector |
| Scale3D | 0x1c | 12 | Vector |

## TransformBase

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Node | 0x0 | 8 | RigTransformConstraint |
| Constraints | 0x8 | 16 | TransformBaseConstraint |

## TransformBaseConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TransformConstraints | 0x0 | 16 |  |

## TurningPlaceData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bIsTurningPlace | 0x0 | 1 |  |
| bIsTurningRight | 0x1 | 1 |  |
| bIsTurningEnter | 0x2 | 1 |  |
| TurnInPlaceBeginYaw | 0x4 | 4 |  |

## TwistConstraint

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| TwistLimitDegrees | 0x14 | 4 | ConstraintBaseParams |
| TwistMotion | 0x18 | 1 | EAngularConstraintMotion |

## TwoVectors

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| v1 | 0x0 | 12 | Vector |
| v2 | 0xc | 12 | Vector |

## URL

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Protocol | 0x0 | 16 | URL |
| Host | 0x10 | 16 | URL |
| Port | 0x20 | 4 | URL |
| Valid | 0x24 | 4 | URL |
| Map | 0x28 | 16 | URL |
| RedirectUrl | 0x38 | 16 |  |
| Op | 0x48 | 16 |  |
| Portal | 0x58 | 16 | FullyLoadedPackagesInfo |

## UpdateLevelStreamingLevelStatus

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PackageName | 0x0 | 8 | UpdateLevelStreamingLevelStatus |
| LodIndex | 0x8 | 4 | UpdateLevelVisibilityLevelInfo |
| bNewShouldBeLoaded | 0xc | 1 |  |
| bNewShouldBeVisible | 0xc | 1 |  |
| bNewShouldBlockOnLoad | 0xc | 1 |  |

## UpdateLevelVisibilityLevelInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| PackageName | 0x0 | 8 | UpdateLevelVisibilityLevelInfo |
| Filename | 0x8 | 8 | CameraCacheEntry |
| bIsVisible | 0x10 | 1 |  |

## Vector

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | Vector |
| Y | 0x4 | 4 | Vector |
| Z | 0x8 | 4 | Guid |

## Vector2D

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | Vector2D |
| Y | 0x4 | 4 | Vector4 |

## Vector4

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| X | 0x0 | 4 | Vector4 |
| Y | 0x4 | 4 | Vector4 |
| Z | 0x8 | 4 | Vector4 |
| W | 0xc | 4 | EncVector |

## VectorRK4SpringInterpolator

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| StiffnessConstant | 0x0 | 4 | VectorRK4SpringInterpolator |
| DampeningRatio | 0x4 | 4 | FloatRK4SpringInterpolator |

## Vector_NetQuantize

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## Vector_NetQuantize10

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## Vector_NetQuantize100

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## Vector_NetQuantizeNormal

| Field | Offset | Size | Type reference |
|---|---:|---:|---|

## VehicleInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| VehicleType | 0x0 | 1 | EAnimVehicleType |
| VehicleId | 0x4 | 4 | VehicleInfo |
| VehicleUpgradeId | 0x8 | 4 | VehicleInfo |
| CampId | 0xc | 4 |  |
| TeamIDArr | 0x10 | 16 |  |
| MarkedCampIDArray | 0x20 | 16 |  |
| bDriverIsCommander | 0x30 | 1 |  |
| DisplayTeamID | 0x34 | 4 | VehicleInfo |
| DisplayPlayerId | 0x38 | 4 |  |
| PlayerMarkingType | 0x3c | 1 |  |

## VisibilityTrackKey

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Time | 0x0 | 4 | ToggleTrackKey |
| Action | 0x4 | 1 | EVisibilityTrackAction |
| ActiveCondition | 0x5 | 1 | EVisibilityTrackCondition |

## WeaponBulletLandingInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| bValid | 0x0 | 1 |  |
| LaunchLocation | 0x4 | 12 | Vector |
| LandingLocation | 0x10 | 12 | Vector_NetQuantize |
| ApexLocation | 0x1c | 12 | Vector_NetQuantize |
| TimeToApex | 0x28 | 4 | WeaponBulletLandingInfo |
| TotalFlightTime | 0x2c | 4 | WeaponFireOptionalData |

## WeaponBulletMediumInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| InitMedium | 0x0 | 1 | EProjectileMedium |
| bPenetrateMedium | 0x1 | 1 |  |
| BorderLoc | 0x4 | 12 | Vector |
| NewMedium | 0x10 | 1 | EProjectileMedium |

## WeaponFireBulletInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| BulletGuid | 0x0 | 8 | WeaponFireBulletInfo |
| BulletId | 0x8 | 8 | WeaponBulletLandingInfo |
| bRotAccurate | 0x10 | 1 |  |
| SpawnLocation | 0x14 | 12 | Vector_NetQuantize |
| SpawnRotation | 0x20 | 12 | Rotator |
| FireRotation | 0x2c | 12 | Rotator |
| OwnerVelocity | 0x38 | 12 | Vector |
| MediumInfo | 0x44 | 20 | WeaponBulletMediumInfo |
| LandingInfo | 0x58 | 48 | WeaponBulletLandingInfo |
| HomingTarget | 0x88 | 8 | Actor |
| PredictHitResult | 0x90 | 136 | HitResult |

## WeaponFireMulticastInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| FireId | 0x8 | 8 | WeaponFireMulticastInfo |
| BulletIndex | 0x10 | 1 |  |
| InitSpeedFor3P | 0x14 | 4 | WeaponFireMulticastInfo |
| NewAmmoCount | 0x18 | 2 | WeaponFireMulticastInfo |
| AmmoId | 0x20 | 8 | WeaponFireMulticastInfo |
| ComboNumber | 0x28 | 1 |  |
| Sim3PContinueFireCount | 0x2a | 2 | WeaponFireMulticastInfo |
| Sim3PContinueSingleFireCount | 0x2c | 2 | WeaponFireBulletInfo |
| BulletInfos | 0x30 | 16 |  |
| OptionalData | 0x40 | 56 | WeaponFireOptionalData |

## WeaponFireOptionalData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| DataOption | 0x0 | 1 |  |
| MovementTimeStamp | 0x4 | 4 | WeaponFireOptionalData |
| CameraLoc | 0x8 | 12 | Vector_NetQuantize100 |
| CameraRot | 0x14 | 8 | Vector2D |
| FireAimRot | 0x1c | 8 | Vector2D |
| CurrentSeed | 0x24 | 4 | WeaponFireOptionalData |
| KickDeltaTime | 0x28 | 4 | WeaponFireOptionalData |
| KickTargetRot | 0x2c | 8 | Vector2D |
| Kick_TransRandIndex | 0x34 | 4 |  |

## WeaponPerk

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Gid | 0x0 | 8 | WeaponPerk |
| ItemID | 0x8 | 8 | WeaponPerk |
| Duability | 0x10 | 2 | WeaponPerk |
| DuabilityMax | 0x12 | 2 | ModularWeaponInfo |
| Level | 0x14 | 1 |  |

## WeaponSkinInfo

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| SkinGid | 0x0 | 8 | WeaponSkinInfo |
| SkinId | 0x8 | 8 | WeaponSkinInfo |
| SkinApperanceId | 0x10 | 8 | WeaponSkinInfo |
| OriginAvatarId | 0x18 | 8 | WeaponSkinInfo |
| MysticalId | 0x20 | 8 | WeaponSkinInfo |
| FancyColorID | 0x28 | 8 | WeaponSkinInfo |
| Wear | 0x30 | 8 | WeaponSkinInfo |
| MaterialRandomSeed | 0x38 | 8 | WeaponSkinInfo |
| Params | 0x40 | 16 |  |
| UniqueNumber | 0x50 | 8 | WeaponSkinInfo |
| KillCnt | 0x58 | 8 | WeaponSkinInfo |
| CustomName | 0x60 | 16 | WeaponSkinInfo |
| SourceType | 0x70 | 8 | PendantInfo |
| PendantMaterialParams | 0x78 | 16 |  |
| PendantInfo | 0x88 | 64 | PendantInfo |
| bLockApperance | 0xc8 | 1 |  |
| SkillSkinEnemyVisible | 0xc9 | 1 |  |
| SkillSkinTeammateVisible | 0xca | 1 |  |

## WeatherSwitchData

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| LastWeatherId | 0x0 | 8 | WeatherSwitchData |
| CurrentWeatherId | 0x8 | 8 | WeatherSwitchData |
| SwitchTime | 0x10 | 4 | WeatherSwitchData |
| Timestamp | 0x14 | 4 | MatchInfo |

## WeightedBlendable

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Weight | 0x0 | 4 | FOscillator |
| CustomViewportLeftTop | 0x4 | 8 | Vector2D |
| CustomViewportSize | 0xc | 8 | Vector2D |
| Object | 0x18 | 8 | Object |

## WeightedBlendables

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| array | 0x0 | 16 |  |

## WorldContext

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| ContextHandle | 0xb0 | 8 | WorldContext |
| TravelURL | 0xb8 | 16 | URL |
| TravelType | 0xc8 | 1 |  |
| LastURL | 0xd0 | 104 | URL |
| LastRemoteURL | 0x138 | 104 | URL |
| PendingNetGame | 0x1a0 | 8 | PendingNetGame |
| PackagesToFullyLoad | 0x1a8 | 16 |  |
| LevelsToLoadForPendingMapChange | 0x1b8 | 16 |  |
| LoadedLevelsForPendingMapChange | 0x1c8 | 16 |  |
| PendingMapChangeFailureDescription | 0x1d8 | 16 | LevelStreamingStatus |
| bShouldCommitPendingMapChange | 0x1e8 | 1 |  |
| ObjectReferencers | 0x1f0 | 16 |  |
| PendingLevelStreamingStatusUpdates | 0x200 | 16 |  |
| GameViewport | 0x210 | 8 | GameViewportClient |
| OwningGameInstance | 0x218 | 8 | GameInstance |
| ActiveNetDrivers | 0x220 | 16 |  |
| PIEInstance | 0x230 | 4 | WorldContext |
| PIEPrefix | 0x238 | 16 | WorldContext |
| RunAsDedicated | 0x24c | 1 |  |
| bWaitingOnOnlineSubsystem | 0x24d | 1 |  |
| AudioDeviceHandle | 0x250 | 4 | WorldContext |
| CustomDescription | 0x258 | 16 | StatColorMapping |

## WrappedStringElement

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Value | 0x0 | 16 | CanvasIcon |
| LineExtent | 0x10 | 8 | Vector2D |

## timecode

| Field | Offset | Size | Type reference |
|---|---:|---:|---|
| Hours | 0x0 | 4 | timecode |
| Minutes | 0x4 | 4 | timecode |
| Seconds | 0x8 | 4 | timecode |
| Frames | 0xc | 4 |  |
| bDropFrameFormat | 0x10 | 1 |  |

