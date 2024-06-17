---
title: Set Morph Targets Min Max Weights
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MLDeformer Morph Model](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MLDeformerMorphModel)

Set the minimum and maximum values that the morph targets weights have seen during training.
We can clamp the network output weights within these ranges to try to make sure that the output doesn't go wild
when we give inputs that are far outside of the range we have seen during training.
The size of the array must equal the number of morph targets, or empty. In case it is empty, clamping will be ignored, even when enabled.

Target is MLDeformer Morph Model

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Min Values | The minimum weigth values, one for each morph target. |
| real | Max Values | The maximum weight values, one for each morph target. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
