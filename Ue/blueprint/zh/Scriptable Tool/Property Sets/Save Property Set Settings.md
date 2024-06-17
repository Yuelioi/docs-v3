---
title: Save Property Set Settings
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Save the values of the specified PropertySet, optionally with a specific SaveKey string.
These saved values can be restored in future Tool invocations based on the SaveKey.

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
| object | Property Set | Save the values of the specified PropertySet, optionally with a specific SaveKey string.These saved values can be restored in future Tool invocations based on the SaveKey. |
