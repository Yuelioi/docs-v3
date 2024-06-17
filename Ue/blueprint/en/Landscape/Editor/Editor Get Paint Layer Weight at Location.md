---
title: Editor Get Paint Layer Weight at Location
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape) > [Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape/Editor)

Gets the landscape paint layer weight value at the given position using LandscapeLayerInfo . Returns 0 in case it fails.

Target is Landscape Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | In Location |  |
| object | Paint Layer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Gets the landscape paint layer weight value at the given position using LandscapeLayerInfo . Returns 0 in case it fails. |
