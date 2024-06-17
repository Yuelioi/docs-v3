---
title: Deactivate Channel
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Deactivates a text to speech channel and stops any vocalized strings on that channel. Future Requests for text to speech functionality will do nothing.
If the provided channel Id does not exist, nothing will happen.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Channel Id | The Id for the channel to deactivate. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
