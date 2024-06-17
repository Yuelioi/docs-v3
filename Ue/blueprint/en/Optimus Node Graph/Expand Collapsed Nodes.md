---
title: Expand Collapsed Nodes
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Optimus Node Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OptimusNodeGraph)

Take a function or subgraph node and expand it in-place, replacing the given function
node. The function definition still remains, if a function node was expanded. If a
sub-graph was expanded, the sub-graph is deleted.

Target is Optimus Node Graph

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Graph Reference Node |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Take a function or subgraph node and expand it in-place, replacing the given functionnode. The function definition still remains, if a function node was expanded. If asub-graph was expanded, the sub-graph is deleted. |
