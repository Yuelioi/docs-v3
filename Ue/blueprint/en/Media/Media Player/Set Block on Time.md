---
display_name: Set Block on Time
order: 71
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Set the time on which to block.

If set, this player will block in TickInput or TickFetch until the video sample
for the specified time are actually available.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Time | The time to block on, or FTimespan::MinValue to disable. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
