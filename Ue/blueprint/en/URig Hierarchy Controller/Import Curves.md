---
title: Import Curves
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Imports all curves from a skeleton to the hierarchy

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Skeleton | The skeleton to import the curves from |
| name | In Name Space | The namespace to prefix the bone names with |
| boolean | Select Curves | If true the curves will be selected upon import |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The keys of the imported elements |
