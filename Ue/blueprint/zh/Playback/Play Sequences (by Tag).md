---
display_name: Play Sequences (by Tag)
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Playback)

Plays all the Sequences that match the given gameplay tag(s)

Target is Ava Sequence Playback Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | In Tag | the tag to match |
| boolean | In Exact Match | whether to only consider sequences that have the tag exactly |
| struct | In Play Settings | the play settings to use for playback |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | an array of the Sequence Players with only valid entries kept |
