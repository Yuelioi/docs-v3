---
display_name: Set Node Keywords by Name
order: 114
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the keywords of a node in the graph.
This causes a NodeKeywordsChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| string | In Keywords |  |
| boolean | Setup Undo Redo |  |
| boolean | Merge Undo Action |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the keywords of a node in the graph.This causes a NodeKeywordsChanged modified event. |
