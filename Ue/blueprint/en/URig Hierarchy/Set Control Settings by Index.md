---
title: Set Control Settings by Index
order: 133
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets the control settings for a given control element by index

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | In Element Index | The index of the control element to set the settings for |
| struct | In Settings | The new control settings value to set |
| boolean | Setup Undo | If true the transform stack will be setup for undo / redo |
| boolean | Force |  |
| boolean | Print Python Commands |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
