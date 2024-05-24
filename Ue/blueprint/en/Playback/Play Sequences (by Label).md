---
display_name: Play Sequences (by Label)
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Playback)

Plays all the sequences that have the provided label

Target is Ava Sequence Playback Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | In Sequence Label | the label of the sequences to play |
| struct | In Play Settings | the play settings to use for playback |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | an array of the Sequence Players with possible invalid/null entries kept so that each Player matches in Index with the input Sequence it is playing |
