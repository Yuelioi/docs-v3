---
title: Add Modifier
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Modifiers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Modifiers)

Adds a new modifier of the specified type. Returns a pointer to the new modifier, or nullptr if a modifier of the specified type already
exists on this node (only one modifier of each type can be added to the node).

Target is Movie Graph Modifier Node

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Modifier Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a new modifier of the specified type. Returns a pointer to the new modifier, or nullptr if a modifier of the specified type alreadyexists on this node (only one modifier of each type can be added to the node). |
