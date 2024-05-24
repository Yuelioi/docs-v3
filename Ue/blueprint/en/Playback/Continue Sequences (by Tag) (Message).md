---
display_name: Continue Sequences (by Tag) (Message)
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Playback)

Triggers Continues in all the sequences matching the provided tag

Target is Ava Sequence Playback Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Tag | the tag to match |
| boolean | In Exact Match | whether to only consider sequences that have the tag exactly |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | the array of the Sequence Players with only valid entries that fired the continue |
