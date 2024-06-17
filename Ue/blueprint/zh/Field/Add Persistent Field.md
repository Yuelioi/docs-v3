---
title: Add Persistent Field
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

AddPersistentField
This function will dispatch a command to the physics thread to apply
a generic evaluation of a user defined field network. This command will be persistent in time and will live until
the component is destroyed or until the RemovePersistenFields function is called. See documentation,
for examples of how to recreate variations of the above generic
fields using field networks

Target is Field System Component

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
