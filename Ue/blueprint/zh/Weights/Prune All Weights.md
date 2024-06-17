---
title: Prune All Weights
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Weights](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Weights)

Remove all weights below the given threshold value, on all vertices.

Target is Skin Weight Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Weight Threshold | vertex weights below this value will be removed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if influences were removed, false otherwise |
