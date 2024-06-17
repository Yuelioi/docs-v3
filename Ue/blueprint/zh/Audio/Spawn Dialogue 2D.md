---
title: Spawn Dialogue 2D
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Spawns a DialogueWave, a special type of Asset that requires Context data in order to resolve a specific SoundBase,
which is then passed on to the new Audio Component. Audio Components created using this function by default will not
have Spatialization applied. Sound instances will begin playing upon spawning this Audio Component.

- Not Replicated.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Dialogue | dialogue to play |
| struct | Context | context the dialogue is to play in |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far in to the dialogue to begin playback at |
| boolean | Auto Destroy | Whether the returned audio component will be automatically cleaned up when the sound finishes (by completing or stopping) or whether it can be reactivated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An audio component to manipulate the spawned sound |
