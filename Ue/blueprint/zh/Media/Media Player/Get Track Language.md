---
title: Get Track Language
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Get the language tag of the specified track.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Track Type | The type of track. |
| integer | Track Index | The index of the track, or INDEX_NONE for the selected one. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Language tag, i.e. "en-US" for English, or "und" for undefined. |
