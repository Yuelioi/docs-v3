---
title: Set Control Target Poses
order: 104
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Calculates and sets an existing control target. This takes the "virtual" position/orientation of the parent
and child and calculates the relative control. Note that this will set bApplyControlPointToTarget to true.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the control to modify. |
| vector | Parent Position | The virtual/target parent position |
| rotator | Parent Orientation | The virtual/target parent orientation |
| vector | Child Position | The virtual/target child position |
| rotator | Child Orientation | The virtual/target child orientation |
| real | Velocity Delta Time | If non-zero, the target velocity will be calculated using the current target position. If zero, the target velocity will be set to zero. |
| boolean | Enable Control | Enables the control if it is currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if the control was found and modified, false if not |
