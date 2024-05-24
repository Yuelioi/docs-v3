---
display_name: Set Rate on Channel
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Sets the current speech rate strings should be vocalized on a text to speech channel.
If the provided channel does not exist, nothing will happen.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Channel Id | The Id for the channel to set the speech rate on. |
| real | Rate | The speech rate to set for the channel. Value will be clamped between 0.0f and 1.0f. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
