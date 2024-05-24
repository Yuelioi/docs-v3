---
display_name: Select Track
order: 70
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Select the active track of the given type.

The selected track will use its currently active format. Active formats will
be remembered on a per track basis. The first available format is active by
default. To switch the track format, use SetTrackFormat instead.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Track Type | The type of track to select. |
| integer | Track Index | The index of the track to select, or INDEX_NONE to deselect. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the track was selected, false otherwise. |
