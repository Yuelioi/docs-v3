---
title: Open Undo Bracket
order: 73
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Opens an undo bracket / scoped transaction for
a series of actions to be performed as one step on the
Undo stack. This is primarily useful for Python.
This causes a UndoBracketOpened modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Title |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Opens an undo bracket / scoped transaction fora series of actions to be performed as one step on theUndo stack. This is primarily useful for Python.This causes a UndoBracketOpened modified event. |
