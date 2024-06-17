---
title: Get Video Track Dimensions
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Get the current dimensions of the specified video track.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Track Index | The index of the track, or INDEX_NONE for the selected one. |
| integer | Format Index | Index of the track format, or INDEX_NONE for the selected one. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Video dimensions (in pixels). |
