---
title: Add Property Set Of Type
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Property Sets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/PropertySets)

Create a new Tool Property Set (ie BP subclass of UScriptableInteractiveToolPropertySet) with the given string Identifier
and attach it to the Tool. The public variables of this Property Set object will appear in (eg) Mode Details Panels, etc.
Multiple Property Sets of the same Type can be attached to a Tool, but each must have a unique Identifier.

Target is Scriptable Interactive Tool

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Property Set Type |  |
| string | Identifier |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Success |  |
| exec | Failure |  |
| object | New Property Set | Create a new Tool Property Set (ie BP subclass of UScriptableInteractiveToolPropertySet) with the given string Identifierand attach it to the Tool. The public variables of this Property Set object will appear in (eg) Mode Details Panels, etc.Multiple Property Sets of the same Type can be attached to a Tool, but each must have a unique Identifier. |
