---
display_name: Gather Subobject Data For Instance
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Gather all subobjects that the given actor instance has. Populates an array of
handles that will have the given context and all it's subobjects.

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Context | Object to gather subobjects for |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Array | Array to populate (will be emptied first) |
