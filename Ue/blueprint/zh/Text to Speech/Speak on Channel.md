---
title: Speak on Channel
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Immediately vocalizes the requested string asynchronously on the requested text to speech channel, interrupting any string that is already being vocalized on the channel.
If the provided channel Id does not exist, nothing will be vocalized.
Before executing this function, a text to speech channel must be added and activated.
To create a platform default text to speech channel, use AddDefaultChannel.
To create a custom text to speech channel with a user-implemented C++ text to speech class, use AddCustomChannel.
This function is not intended for long strings that span multiple sentences or paragraphs.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Channel Id | The Id of the channel to speak on. |
| string | String to Speak | The string to speak on the requested channel. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
