---
title: Remove Labeled Edge
order: 62
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Like AddLabeledEdge, removes the given connection between Node A and Node B (for the specified pins by name).

Target is Movie Graph Config

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | From Node |  |
| name | From Pin Name |  |
| object | To Node |  |
| name | To Pin Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Like AddLabeledEdge, removes the given connection between Node A and Node B (for the specified pins by name). |
