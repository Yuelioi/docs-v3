---
display_name: Set Body Modifiers in Set Physics Blend Weight
order: 76
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Sets the physics blend weight for body modifiers

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Set | The set of body modifiers to modify. Standard sets will include "All" and things like "ArmLeft", depending on how body modifiers have been created. |
| real | Physics Blend Weight | The blend weight between the body transform coming from animation and that coming from simulation. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
