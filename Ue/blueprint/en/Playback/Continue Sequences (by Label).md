---
display_name: Continue Sequences (by Label)
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Playback)

Triggers Continue for the playing sequences that match the given label

Target is Ava Sequence Playback Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | In Sequence Label | the label of the sequences to continue |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | the sequence players that fired the continue, or null if there were no active players |
