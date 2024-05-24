---
display_name: Set Node Description by Name
order: 112
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the keywords of a node in the graph.
This causes a NodeDescriptionChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| string | In Description |  |
| boolean | Setup Undo Redo |  |
| boolean | Merge Undo Action |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the keywords of a node in the graph.This causes a NodeDescriptionChanged modified event. |
