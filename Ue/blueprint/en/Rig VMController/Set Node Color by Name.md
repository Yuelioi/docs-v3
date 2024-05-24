---
display_name: Set Node Color by Name
order: 110
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the color of a node in the graph by name.
This causes a NodeColorChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| linearcolor | In Color |  |
| boolean | Setup Undo Redo |  |
| boolean | Merge Undo Action |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the color of a node in the graph by name.This causes a NodeColorChanged modified event. |
