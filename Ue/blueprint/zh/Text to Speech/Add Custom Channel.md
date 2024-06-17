---
title: Add Custom Channel
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Creates a new text to speech channel where text to speech requests are fulfilled by a user implemented C++ text to speech class.
If you have not specified a custom text to speech class to be used, use AddDefaultChannel instead.
This will not add a channel if the channel Id is not unique or if the user has not specified a custom text to speech class to be used in ITextToSpeechModule.
Newly added channels must be activated to use text to speech functionalities.
See: ITextToSpeechModule, AddDefaultChannel, ActivateChannel, ActivateAllChannels

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
