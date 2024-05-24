---
display_name: Force Property Set Update by Name
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Force the Property Set associated with the given Identifier to be updated.
This may be necessary if you change the Property Set values directly via Blueprints, and want to
see your changes reflected in (eg) a Details Panel showing the Tool Property values.
Currently these changes cannot be detected automatically, necessitating this function.

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
| exec | Out |  |
