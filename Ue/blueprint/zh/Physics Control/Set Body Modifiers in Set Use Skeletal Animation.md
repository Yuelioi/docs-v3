---
display_name: Set Body Modifiers in Set Use Skeletal Animation
order: 78
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
| name | Set | The set of body modifiers to modify. Standard sets will include "All" and things like "ArmLeft", depending on how body modifiers have been created. |
| boolean | Use Skeletal Animation | Whether the kinematic target is specified in the frame of the skeletal animation, rather than world space. Only relevant if the body is part of a skeletal mesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
