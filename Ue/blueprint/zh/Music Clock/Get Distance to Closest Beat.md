---
title: Get Distance to Closest Beat
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Gets a value expressed in beats between 0-1 that indicates how close we are to the closest beat (current beat or next beat). // Note: Not const as it might cause the clock to update from its source.

Target is Music Clock

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Timebase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Gets a value expressed in beats between 0-1 that indicates how close we are to the closest beat (current beat or next beat). // Note: Not const as it might cause the clock to update from its source. |
