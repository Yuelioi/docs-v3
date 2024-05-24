---
display_name: Get Volume on Channel
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Returns the current volume strings are vocalized on a text to speech channel. Value is between 0.0f and 1.0f.
If the provided channel Id doesn't exist, 0.0f will be returned.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Channel Id | The Id for the channel to retrieve the volume from. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value |  |
