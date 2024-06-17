---
title: Mirror Elements
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Mirrors the given elements

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Keys | The keys of the elements to mirror |
| struct | In Settings | The settings to use for the mirror operation |
| boolean | Select New Elements | If set to true the new elements will be selected |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Commands |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The keys of the mirrored items |
