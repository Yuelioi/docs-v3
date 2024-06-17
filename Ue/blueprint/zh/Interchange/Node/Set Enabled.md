---
title: Set Enabled
order: 68
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Node](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/Node_1)

Determine whether this node should be part of the import or export process.

Target is Interchange Base Node

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Is Enabled | If true, this node is imported or exported. If false, it is discarded. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the attribute was set, or false otherwise. |
