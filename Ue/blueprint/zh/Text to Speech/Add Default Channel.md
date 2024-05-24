---
display_name: Add Default Channel
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Creates a new channel for text to speech requests to be made to a platform C++ text to speech class.
This will not create the channel if the provided channel id is not unique.
Newly added channels must be activated to use text to speech functionalities.
For out-of-the-box text to speech support, this is most likely the channel creation method you want.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | New Channel Id |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
