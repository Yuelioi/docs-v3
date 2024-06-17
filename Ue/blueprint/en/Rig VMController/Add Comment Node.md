---
title: Add Comment Node
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Adds a Comment Node to the edited Graph.
Comments can be used to annotate the Graph.
This causes a NodeAdded modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Comment Text |  |
| vector2d struct | In Position |  |
| vector2d struct | In Size |  |
| linearcolor | In Color |  |
| string | In Node Name |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a Comment Node to the edited Graph.Comments can be used to annotate the Graph.This causes a NodeAdded modified event. |
