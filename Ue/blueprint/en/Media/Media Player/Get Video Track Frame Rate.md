---
display_name: Get Video Track Frame Rate
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Get the frame rate of the specified video track.

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
| real | Return Value | Frame rate (in frames per second). |
