---
title: Set Volume on Channel
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Text to Speech](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TexttoSpeech)

Sets the volume for strings vocalized on a text to speech channel.
If the provided channel Id does not exist, nothing will happen.

Target is Text to Speech Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Channel Id | The Id for the channel to set for. |
| real | Volume | The volume to be set on the channel. The value will be clamped between 0.0f and 1.0f. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
