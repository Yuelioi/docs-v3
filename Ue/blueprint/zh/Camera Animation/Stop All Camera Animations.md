---
display_name: Stop All Camera Animations
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CameraAnimation)

Stop all camera animation instances.

Target is Gameplay Cameras Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Player Controller | The player controller on which to play the animation. |
| boolean | Immediate | True to stop it right now and ignore blend out, false to let it blend out as indicated. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
