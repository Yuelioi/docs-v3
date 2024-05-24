---
display_name: Remove Property Set by Name
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Remove a Property Set from the current Tool, found via it's unique Identifier.
Unless the Property Set absolutely needs to stop existing, it is likely preferable to use SetPropertySetVisibleByName() to simply hide it.

Target is Scriptable Interactive Tool

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Identifier |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Success |  |
| exec | Failure |  |
