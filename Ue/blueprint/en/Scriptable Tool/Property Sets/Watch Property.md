---
display_name: Watch Property
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Watch any Property in a PropertySet for changes. This function handles most basic
properties, as well as Struct and Array properties, at some cost. The OnModified
delegate cannot be passed the new property value, it must be fetched from the PropertySet.

Note also that in the case of Structs and Arrays, changes are currently detected by hashes,
and there is always a small chance of hash collision.

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
