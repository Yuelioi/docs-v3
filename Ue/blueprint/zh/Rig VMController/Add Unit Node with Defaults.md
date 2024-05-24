---
display_name: Add Unit Node with Defaults
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Adds a Function / Struct Node to the edited Graph.
UnitNode represent a RIGVM_METHOD declaration on a USTRUCT.
This causes a NodeAdded modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Script Struct |  |
| string | In Defaults |  |
| name | In Method Name |  |
| vector2d struct | In Position |  |
| string | In Node Name |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a Function / Struct Node to the edited Graph.UnitNode represent a RIGVM_METHOD declaration on a USTRUCT.This causes a NodeAdded modified event. |
