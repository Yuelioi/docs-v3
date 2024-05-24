---
display_name: Get Auto Size End Frame Seconds
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Section](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Section)

Get end time of the AutoSize seconds. Will throw an exception if section has no end frame, use GetAutoSizeHasEndFrame to check first.

Target is Movie Scene Section Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Section | The section being queried |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | The end frame of the AutoSize data in seconds. |
