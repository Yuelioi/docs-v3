---
display_name: Random Sobol Cell 3D
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | Which sequential point in the cell (starting at 0) |
| integer | Num Cells | Size of cell grid, 1 to 1024. Rounded up to the next power of two |
| vector | Cell | Give a point from this integer grid cell |
| vector | Seed | Random 3D seed (components in the range 0-1) to randomize across multiple sequences |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Sobol-distributed random 3D vector in the given grid cell |
