---
display_name: Set View Field
order: 81
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Set the field of view (only for 360 videos).

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Horizontal | Horizontal field of view (in Euler degrees). |
| real | Vertical | Vertical field of view (in Euler degrees). |
| boolean | Absolute |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true on success, false otherwise. |
