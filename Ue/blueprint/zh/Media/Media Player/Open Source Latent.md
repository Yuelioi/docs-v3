---
display_name: Open Source Latent
order: 59
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Open the specified media source with options using a latent action.

A result of true indicates that the player successfully completed all requested operations.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Media Source | The media source to open. |
| struct | Options | The media player options to apply. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| boolean | Success | All requested operations have completed successfully. |
