---
title: Set Body Modifiers Use Skeletal Animation
order: 72
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Sets whether body modifiers should use skeletal animation for their kinematic targets

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Names | The names of the body modifiers to access. Note that if you have these in a FPhysicsControlNameArray then it can be split. |
| boolean | Use Skeletal Animation | Whether the kinematic target is specified in the frame of the skeletal animation, rather than world space. Only relevant if the body is part of a skeletal mesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
