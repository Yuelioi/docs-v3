---
display_name: Next Sobol Float
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | Which sequential point |
| integer | Dimension | Which Sobol dimension (0 to 15) |
| real | Previous Value | The Sobol value for Index-1 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Sobol-distributed random number between 0 and 1 |
