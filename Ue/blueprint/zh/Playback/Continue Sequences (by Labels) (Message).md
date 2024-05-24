---
display_name: Continue Sequences (by Labels) (Message)
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Playback)

Triggers Continues in multiple playing sequences given by an array of sequence labels

Target is Ava Sequence Playback Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Sequence Labels | the array of sequence labels to trigger continue (must be an active sequence playing) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | the sequence player array that fired the continue. It might have possible invalid/null entries so that each Player matches in Index with the input Sequence labels |
