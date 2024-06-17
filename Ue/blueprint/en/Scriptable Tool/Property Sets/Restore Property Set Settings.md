---
title: Restore Property Set Settings
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Restore the values of the specified PropertySet, optionally with a specific SaveKey string.
This will have no effect unless SavePropertySetSettings() has been called on a compatible Property Set
in the same Engine session (ie in a previous invocation of the Tool, or another Tool that uses the same Property Set)

Target is Scriptable Interactive Tool

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Property Set |  |
| string | Save Key |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Property Set | Restore the values of the specified PropertySet, optionally with a specific SaveKey string.This will have no effect unless SavePropertySetSettings() has been called on a compatible Property Setin the same Engine session (ie in a previous invocation of the Tool, or another Tool that uses the same Property Set) |
