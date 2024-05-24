---
display_name: Set Control Target Positions and Orientations from Array
order: 107
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Calls SetControlTargetPositionAndOrientation for each element of the control names, positions and orientations.
These array should match in size.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Names |  |
| vector | Positions |  |
| rotator | Orientations |  |
| real | Velocity Delta Time |  |
| boolean | Enable Control |  |
| boolean | Apply Control Point to Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the control/position/orientation arrays match, false if they don't. |
