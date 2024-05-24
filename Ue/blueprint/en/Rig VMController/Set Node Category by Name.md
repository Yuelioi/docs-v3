---
display_name: Set Node Category by Name
order: 108
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the category of a node in the graph.
This causes a NodeCategoryChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| string | In Category |  |
| boolean | Setup Undo Redo |  |
| boolean | Merge Undo Action |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the category of a node in the graph.This causes a NodeCategoryChanged modified event. |
