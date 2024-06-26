---
title: Add Injected Node
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Adds a Function / Struct Node to the edited Graph as an injected node
UnitNode represent a RIGVM_METHOD declaration on a USTRUCT.
This causes a NodeAdded modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Pin Path |  |
| boolean | As Input |  |
| object | In Script Struct |  |
| name | In Method Name |  |
| name | In Input Pin Name |  |
| name | In Output Pin Name |  |
| string | In Node Name |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a Function / Struct Node to the edited Graph as an injected nodeUnitNode represent a RIGVM_METHOD declaration on a USTRUCT.This causes a NodeAdded modified event. |
