---
title: Set Local Transform by Index
order: 151
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets the local current or initial transform for a given element index.

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | In Element Index | The index of the element to set the transform for |
| transform | In Transform | The new transform value to set |
| boolean | Initial | If true the initial transform will be used |
| boolean | Affect Children | If set to false children will not move (maintain global). |
| boolean | Setup Undo | If true the transform stack will be setup for undo / redo |
| boolean | Print Python Commands |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
