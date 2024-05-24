---
display_name: Next Sobol Cell 2D
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | Which sequential point |
| integer | Num Cells | Size of cell grid, 1 to 32768. Rounded up to the next power of two |
| vector2d struct | Previous Value | The Sobol value for Index-1 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | Sobol-distributed random 2D position in the same grid cell |
