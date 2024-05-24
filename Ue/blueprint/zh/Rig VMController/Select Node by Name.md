---
display_name: Select Node by Name
order: 98
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Selects a single node in the graph by name.
This causes a NodeSelected / NodeDeselected modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| boolean | Select |  |
| boolean | Setup Undo Redo |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Selects a single node in the graph by name.This causes a NodeSelected / NodeDeselected modified event. |
