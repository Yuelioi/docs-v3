---
title: Get Playback Time Range
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Blueprint accessible version of GetPlaybackTimeRange.
This returns the range truncated into a blueprint usable float interval and should not
be used for live streams as 32 bit floats can not store wallclock times with enough precision.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | In Range to Get |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Blueprint accessible version of GetPlaybackTimeRange.This returns the range truncated into a blueprint usable float interval and should notbe used for live streams as 32 bit floats can not store wallclock times with enough precision. |
