---
display_name: Add Link
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Adds a link to the graph.
This causes a LinkAdded modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Output Pin Path |  |
| string | In Input Pin Path |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |
| enum | In User Direction |  |
| boolean | Create Cast Node |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Adds a link to the graph.This causes a LinkAdded modified event. |
