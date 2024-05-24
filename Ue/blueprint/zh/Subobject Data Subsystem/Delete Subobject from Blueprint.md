---
display_name: Delete Subobject from Blueprint
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Attempts to delete the given subobject from its blueprint context

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Context Handle | The owning context of the subobjects that should be removed |
| struct | Subobject to Delete | The subobject handles that should be deleted |
| object | BPContext | The blueprint context for the given |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The number of subobjects successfully deleted |
