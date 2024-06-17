---
title: Set Track Format
order: 79
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Set the format on the specified track.

Selecting the format will not switch to the specified track. To switch
tracks, use SelectTrack instead. If the track is already selected, the
format change will be applied immediately.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Track Type | The type of track to update. |
| integer | Track Index | The index of the track to update. |
| integer | Format Index | The index of the format to select (must be valid). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the track was selected, false otherwise. |
