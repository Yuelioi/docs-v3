---
title: Create TRSGizmo
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool) > [Gizmos](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool/Gizmos)

Create a Translate/Rotate/Scale Gizmo with the given Options at the specified InitialTransform.
The Gizmo must be given a unique Identifier, which will be used to access it in other functions.
The Gizmo can be explicitly destroyed with DestroyTRSGizmo(), or it will be
automatically destroyed when the Tool exits

Target is Scriptable Interactive Tool

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Identifier |  |
| transform | Initial Transform |  |
| struct | Gizmo Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Success |  |
| exec | Failure |  |
