---
title: Random Sobol Float
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | Which sequential point |
| integer | Dimension | Which Sobol dimension (0 to 15) |
| real | Seed | Random seed (in the range 0-1) to randomize across multiple sequences |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Sobol-distributed random number between 0 and 1 |
