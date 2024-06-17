---
title: Set Video Track Frame Rate
order: 80
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Set the frame rate of the specified video track.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Track Index | The index of the track, or INDEX_NONE for the selected one. |
| integer | Format Index | Index of the track format, or INDEX_NONE for the selected one. |
| real | Frame Rate | The frame rate to set (must be in range of format's supported frame rates). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true on success, false otherwise. |
