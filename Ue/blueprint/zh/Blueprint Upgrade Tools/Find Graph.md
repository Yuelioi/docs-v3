---
title: Find Graph
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Blueprint Upgrade Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/BlueprintUpgradeTools)

Finds the graph with the given name on the blueprint. Null if it doesn't have one.

Target is Blueprint Editor Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Blueprint | Blueprint to search |
| name | Graph Name | The name of the graph to search for |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | UEdGraph\* Pointer to the graph with the given name, null if not found |
