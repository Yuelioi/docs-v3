---
display_name: Set Body Modifier Use Skeletal Animation
order: 66
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Sets whether a body modifier should use skeletal animation for its kinematic targets

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the body modifier to access. |
| boolean | Use Skeletal Animation | Whether the kinematic target is specified in the frame of the skeletal animation, rather than world space. Only relevant if the body is part of a skeletal mesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the body modifier was found, false if not |
