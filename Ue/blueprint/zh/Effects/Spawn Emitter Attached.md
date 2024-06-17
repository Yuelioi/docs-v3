---
title: Spawn Emitter Attached
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Effects](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Effects)

Plays the specified effect attached to and following the specified component. The system will go away when the effect is complete. Does not replicate.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Emitter Template | particle system to create |
| object | Attach to Component |  |
| name | Attach Point Name | Optional named point within the AttachComponent to spawn the emitter at |
| vector | Location | Depending on the value of LocationType this is either a relative offset from the attach component/point or an absolute world location that will be translated to a relative offset (if LocationType is KeepWorldPosition). |
| rotator | Rotation | Depending on the value of LocationType this is either a relative offset from the attach component/point or an absolute world rotation that will be translated to a relative offset (if LocationType is KeepWorldPosition). |
| vector | Scale | Depending on the value of LocationType this is either a relative scale from the attach component or an absolute world scale that will be translated to a relative scale (if LocationType is KeepWorldPosition). |
| enum | Location Type | Specifies whether Location is a relative offset or an absolute world position |
| boolean | Auto Destroy | Whether the component will automatically be destroyed when the particle system completes playing or whether it can be reactivated |
| enum | Pooling Method | Method used for pooling this component. Defaults to none. |
| boolean | Auto Activate | Whether the component will be automatically activated on creation. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
