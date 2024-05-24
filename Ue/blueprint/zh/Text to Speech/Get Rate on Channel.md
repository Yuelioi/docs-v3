---
display_name: Get Rate on Channel
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Returns the current speech rate strings are vocalized on a text to speech channel. Value is between 0.0 and 1.0.
If the provided channel Id does not exist, 0.0f will be returned.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Channel Id | The Id for the channel to get the speech rate from. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value |  |
