---
display_name: Get Start Frame Seconds
order: 48
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Section](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Section)

Get start time in seconds. Will throw an exception if section has no start frame, use HasStartFrame to check first.

Target is Movie Scene Section Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Section | The section within which to get the start time |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Start time of this section |
