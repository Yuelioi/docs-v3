---
title: Get Moving Ranges from Root Motion
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Extractor Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionExtractorUtility)

Returns the ranges (X/Start to Y/End) in the specified animation sequence where the animation is considered moving.

Target is Motion Extractor Utility Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Anim Sequence | Anim sequence to check |
| real | Stop Speed Threshold | Root motion speed over which the animation is considered moving. |
| real | Sample Rate | Sample rate of the animation. It's recommended to use high values if the animation has very sudden direction changes. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector2d struct | Return Value |  |
