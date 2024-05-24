---
display_name: Set Node Position by Name
order: 116
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the position of a node in the graph by name.
This causes a NodePositionChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| vector2d struct | In Position |  |
| boolean | Setup Undo Redo |  |
| boolean | Merge Undo Action |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the position of a node in the graph by name.This causes a NodePositionChanged modified event. |
