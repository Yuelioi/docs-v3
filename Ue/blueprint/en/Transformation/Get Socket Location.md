---
title: Get Socket Location
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Get world-space socket or bone location.

Target is Scene Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | In Socket Name | Name of the socket or the bone to get the transform |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Socket transform in world space if socket is found. Otherwise it will return component's transform in world space. |
