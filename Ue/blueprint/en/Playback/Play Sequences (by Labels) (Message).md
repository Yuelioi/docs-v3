---
display_name: Play Sequences (by Labels) (Message)
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Playback)

Plays multiple Sequences by an array of sequence labels

Target is Ava Sequence Playback Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Sequence Labels | the array of sequence labels to play |
| struct | In Play Settings | the play settings to use for playback |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | an array of the Sequence Players with possible invalid/null entries kept so that each Player matches in Index with the input Sequence it is playing |
