---
display_name: Add Physics Field
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

AddPhysicsField
This function will dispatch a command to the physics thread to apply
a generic evaluation of a user defined transient field network. See documentation,
for examples of how to recreate variations of the above generic
fields using field networks

Target is Geometry Collection Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Field | Is this force enabled for evaluation. |
| enum | Physics Type | Type of field supported by the solver. |
| object | Meta Data | Meta data used to assist in evaluation |
| object | Field Node | Base evaluation node for the field network. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
