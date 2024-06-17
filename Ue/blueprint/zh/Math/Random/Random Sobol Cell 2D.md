---
title: Random Sobol Cell 2D
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | Which sequential point in the cell (starting at 0) |
| integer | Num Cells | Size of cell grid, 1 to 32768. Rounded up to the next power of two |
| vector2d struct | Cell | Give a point from this integer grid cell |
| vector2d struct | Seed | Random 2D seed (components in the range 0-1) to randomize across multiple sequences |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | Sobol-distributed random 2D position in the given grid cell |
