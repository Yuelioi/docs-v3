---
title: Get Effective Output Resolution
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

In case of overscan percentage being higher than 0, additional pixels are rendered. This function returns the resolution with overscan taken into account.

Target is Movie Graph Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Evaluated Graph | The evaluated graph that will provide context for resolving the resolution |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The output resolution, taking into account overscan |
