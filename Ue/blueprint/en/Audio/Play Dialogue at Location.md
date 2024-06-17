---
title: Play Dialogue at Location
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Plays a dialogue at the given location. This is a fire and forget sound and does not travel with any actor.
Replication is also not handled at this point.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Dialogue | dialogue to play |
| struct | Context | context the dialogue is to play in |
| vector | Location | World position to play dialogue at |
| rotator | Rotation | World rotation to play dialogue at |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far in to the dialogue to begin playback at |
| object | Attenuation Settings | Override attenuation settings package to play sound with |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
