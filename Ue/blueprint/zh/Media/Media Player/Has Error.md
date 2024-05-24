---
display_name: Has Error
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Check whether the player is in an error state.

When the player is in an error state, no further operations are possible.
The current media must be closed, and a new media source must be opened
before the player can be used again. Errors are usually caused by faulty
media files or interrupted network connections.

See: IsReady

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Check whether the player is in an error state.When the player is in an error state, no further operations are possible.The current media must be closed, and a new media source must be openedbefore the player can be used again. Errors are usually caused by faultymedia files or interrupted network connections.@see IsReady |
