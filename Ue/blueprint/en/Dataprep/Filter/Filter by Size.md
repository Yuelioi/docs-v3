---
title: Filter by Size
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Filter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/Filter)

Filter the array based on the geometry size.

Target is Datasmith Data Preparation Filter Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Array | Array of Actors or StaticMeshes to filter. The array will not change. |
| enum | Size Source | The reference dimension |
| enum | Filter Mode | How to compare the object size with the threshold |
| real | Threshold | Limit value |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The filtered list. |
