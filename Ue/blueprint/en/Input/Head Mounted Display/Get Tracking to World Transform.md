---
title: Get Tracking to World Transform
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

Returns a transform that can be used to convert points from tracking space to world space.
Does NOT include the set WorldToMeters scale, as that is added in by the backing XR system to their tracking space poses.

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Return Value | Returns a transform that can be used to convert points from tracking space to world space.Does NOT include the set WorldToMeters scale, as that is added in by the backing XR system to their tracking space poses. |
