---
display_name: Deproject Screen to World
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Camera)

Transforms the given 2D screen space coordinate into a 3D world-space point and direction.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Player | Deproject using this player's view. |
| vector2d struct | Screen Position | 2D screen space to deproject. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | World Position | (out) Corresponding 3D position in world space. |
| vector | World Direction | (out) World space direction vector away from the camera at the given 2d point. |
| boolean | Return Value |  |
