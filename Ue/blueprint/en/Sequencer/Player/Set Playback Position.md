---
display_name: Set Playback Position
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Player)

Set the current time of the player by evaluating from the current time to the specified time, as if the sequence is playing.
Triggers events that lie within the evaluated range. Does not alter the persistent playback status of the player (IsPlaying).

Target is Movie Scene Sequence Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Playback Params | The position settings (ie. the position to set playback to) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
