---
display_name: Open Playlist Index
order: 57
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Open a particular media source in the specified play list.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Playlist | The play list to open. |
| integer | Index | The index of the source to open. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the source will be opened, false otherwise. |
