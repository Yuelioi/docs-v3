---
display_name: Import Bones
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Imports an existing skeleton to the hierarchy

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Skeleton | The skeleton to import |
| name | In Name Space | The namespace to prefix the bone names with |
| boolean | Replace Existing Bones | If true existing bones will be removed |
| boolean | Remove Obsolete Bones | If true bones non-existent in the skeleton will be removed from the hierarchy |
| boolean | Select Bones | If true the bones will be selected upon import |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command | If set to true a python command equivalent to this call will be printed out |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The keys of the imported elements |
