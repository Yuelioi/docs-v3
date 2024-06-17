---
title: Set Control Offset Transform
order: 126
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets the offset transform for a given control element by key

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Key | The key of the control element to set the offset transform for |
| transform | In Transform | The new offset transform value to set |
| boolean | Initial | If true the initial value will be used |
| boolean | Affect Children | If set to false children will not move (maintain global). |
| boolean | Setup Undo | If true the transform stack will be setup for undo / redo |
| boolean | Print Python Commands |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
