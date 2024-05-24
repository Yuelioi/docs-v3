---
display_name: Get End Frame Seconds
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Section](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Section)

Get end time in seconds. Will throw an exception if section has no end frame, use HasEndFrame to check first.

Target is Movie Scene Section Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Section | The section within which to get the end time |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | End time of this section |
