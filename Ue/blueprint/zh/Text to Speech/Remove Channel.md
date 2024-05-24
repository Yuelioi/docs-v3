---
display_name: Remove Channel
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Removes a text to speech channel, preventing all further requests for text to speech functionality from the channel.
If the provided channel Id does not exist, nothing will happen.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Channel Id | The Id for the channel you want removed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
