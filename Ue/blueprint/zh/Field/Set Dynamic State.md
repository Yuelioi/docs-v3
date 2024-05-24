---
display_name: Set Dynamic State
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

SetDynamicState
This function will dispatch a command to the physics thread to apply
a kinematic to dynamic state change for the particles within the field.

Target is Field System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Field | Is this force enabled for evaluation. |
| vector | Center Position | The location of the command |
| real | Field Radius | Radial influence from the position |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
