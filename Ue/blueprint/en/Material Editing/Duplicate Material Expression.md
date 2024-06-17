---
title: Duplicate Material Expression
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Material Editing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MaterialEditing)

Duplicates the provided material expression adding it to the same material / material function, and copying parameters.
Note: Does not duplicate transient properties (Ex: GraphNode).

Target is Material Editing Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Material | Material asset to add an expression to |
| object | Material Function | Specified if adding an expression to a MaterialFunction, used as Outer for new expression object |
| object | Expression |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
