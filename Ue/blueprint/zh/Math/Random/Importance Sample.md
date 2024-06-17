---
title: Importance Sample
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Distribute sample points proportional to Texture2D luminance.

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Texture |  |
| vector2d struct | Rand | Random 2D point with components evenly distributed between 0 and 1 |
| integer | Samples | Total number of samples that will be used |
| real | Intensity | Total intensity for light |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Sample Position |  |
| linearcolor | Sample Color |  |
| real | Sample Intensity |  |
| real | Sample Size |  |
