---
title: Get Effective Frame Rate
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Returns the frame rate override from the Primary Configuration (if any) or the Sequence frame rate if no override is specified.
This should be treated as the actual output framerate of the overall Pipeline.

Target is Movie Pipeline Primary Config

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | In Sequence |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Returns the frame rate override from the Primary Configuration (if any) or the Sequence frame rate if no override is specified.This should be treated as the actual output framerate of the overall Pipeline. |
