---
title: Next Sobol Cell 3D
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | Which sequential point |
| integer | Num Cells | Size of cell grid, 1 to 1024. Rounded up to the next power of two |
| vector | Previous Value | The Sobol value for Index-1 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Sobol-distributed random 3D position in the same grid cell |
