---
title: Get Song Remaining Ms
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Returns the remaining time until the end of the MIDI in milliseconds based on the timestamp corresponding to the passed Timebase // Note: Not const as it might cause the clock to update from its source.

Target is Music Clock

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Timebase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Returns the remaining time until the end of the MIDI in milliseconds based on the timestamp corresponding to the passed Timebase // Note: Not const as it might cause the clock to update from its source. |
