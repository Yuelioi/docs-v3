---
title: Set Submix Effect Chain Override
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Effects](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Effects)

Sets a submix effect chain override on the given submix. The effect chain will cross fade from the base effect chain or current override to the new override.

Target is Audio Mixer Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sound Submix |  |
| object | Submix Effect Preset Chain |  |
| real | Fade Time Sec |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
