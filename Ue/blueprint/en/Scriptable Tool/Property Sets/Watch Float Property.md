---
display_name: Watch Float Property
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Watch a Float-valued Property for changes (double precision)

Target is Scriptable Interactive Tool

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Property Set | the Property Set which contains the desired Property to watch. |
| string | Property Name | the string name of the Property in the given Property Set |
| delegate | On Modified | this delegate will be called if the Property value changes. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Property Set |  |
