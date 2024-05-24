---
display_name: Has Mapping Context (Message)
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Mapping Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/MappingQueries)

Check if a mapping context is applied to this subsystem's owner.

Target is Enhanced Input Subsystem Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Mapping Context | The mapping context to search for on the subsystem's owner. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Out Found Priority | The priority of the mapping context if it is applied. -1 if the context is not applied |
| boolean | Return Value | True if the mapping context is applied |
