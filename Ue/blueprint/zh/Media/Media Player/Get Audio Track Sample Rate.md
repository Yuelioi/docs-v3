---
display_name: Get Audio Track Sample Rate
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Get the sample rate of the specified audio track.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Track Index | Index of the audio track, or INDEX_NONE for the selected one. |
| integer | Format Index | Index of the track format, or INDEX_NONE for the selected one. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Samples per second. |
