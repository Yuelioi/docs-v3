---
title: Spawn Dialogue at Location
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Spawns a DialogueWave, a special type of Asset that requires Context data in order to resolve a specific SoundBase,
which is then passed on to the new Audio Component. This function allows users to create and play Audio Components at a
specific World Location and Rotation. Useful for spatialized and/or distance-attenuated dialogue.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Dialogue | Dialogue to play |
| struct | Context | Context the dialogue is to play in |
| vector | Location | World position to play dialogue at |
| rotator | Rotation | World rotation to play dialogue at |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far into the dialogue to begin playback at |
| object | Attenuation Settings | Override attenuation settings package to play sound with |
| boolean | Auto Destroy | Whether the returned audio component will be automatically cleaned up when the sound finishes (by completing or stopping) or whether it can be reactivated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Audio Component to manipulate the playing dialogue with |
