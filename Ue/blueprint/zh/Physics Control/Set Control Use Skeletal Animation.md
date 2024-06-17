---
title: Set Control Use Skeletal Animation
order: 116
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Sets whether or not the control should use skeletal animation for the targets

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the control to modify. |
| boolean | Use Skeletal Animation | If true then the targets will be a combination of the skeletal animation (if there is any) and the control target that has been set |
| real | Skeletal Animation Velocity Multiplier | If skeletal animation is being used, then this determines the amount of velocity extracted from the animation that is used as targets for the controls |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the control was found and modified, false if not |
