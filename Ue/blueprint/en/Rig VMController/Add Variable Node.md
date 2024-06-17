---
title: Add Variable Node
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Adds a Variable Node to the edited Graph.
Variables represent local work state for the function and
can be read from and written to.
This causes a NodeAdded modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Variable Name |  |
| string | In CPPType |  |
| object | In CPPType Object |  |
| boolean | Is Getter |  |
| string | In Default Value |  |
| vector2d struct | In Position |  |
| string | In Node Name |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a Variable Node to the edited Graph.Variables represent local work state for the function andcan be read from and written to.This causes a NodeAdded modified event. |
