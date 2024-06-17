---
title: Get Effective Output Resolution
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

In case of Overscan percentage being higher than 0 we render additional pixels. This function returns the resolution with overscan taken into account.

Target is Movie Pipeline Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Primary Config |  |
| object | In Pipeline Executor Shot |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | In case of Overscan percentage being higher than 0 we render additional pixels. This function returns the resolution with overscan taken into account. |
