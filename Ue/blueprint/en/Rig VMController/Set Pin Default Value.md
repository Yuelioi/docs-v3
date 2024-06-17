---
title: Set Pin Default Value
order: 121
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the default value of a pin given its pinpath.
This causes a PinDefaultValueChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Pin Path |  |
| string | In Default Value |  |
| boolean | Resize Arrays |  |
| boolean | Setup Undo Redo |  |
| boolean | Merge Undo Action |  |
| boolean | Print Python Command |  |
| boolean | Set Value on Linked Pins |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the default value of a pin given its pinpath.This causes a PinDefaultValueChanged modified event. |
