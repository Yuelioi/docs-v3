---
display_name: Set Control Target Position
order: 106
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies an existing control target - i.e. what it is driving towards, relative to the parent object

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the control to modify. |
| vector | Position | The new position target for the control |
| real | Velocity Delta Time | If non-zero, the target velocity will be calculated using the current target position. If zero, the target velocity will be set to zero. |
| boolean | Enable Control | Enables the control if it is currently disabled |
| boolean | Apply Control Point to Target | If true, then the target position/orientation is treated as a "virtual" object, where the system attempts to move the object to match the pose of this "virtual" object that has been placed at the target transform. Use this when you want to specify the target transform for the object as a whole. If false, then the target transform is used as is, and the system drives the control point towards this transform. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the control was found and modified, false if not |
