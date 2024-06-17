---
title: Get Position to Option Map from Actor
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Wave Function Collapse](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WaveFunctionCollapse)

Get PositionToOptionsMap from a given actor that has ISM components.
This is useful when you want to derive neighboring tile data from a WFC-solved actor to be used for post processing.
This will only evaluate ISM components.

Target is Wave Function Collapse BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Actor | Actor with ISM components |
| real | Tile Size | distance between tiles |
| struct | Position to Option Map |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
