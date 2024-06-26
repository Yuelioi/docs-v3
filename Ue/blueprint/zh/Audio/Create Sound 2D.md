---
title: Create Sound 2D
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

This function allows users to create Audio Components in advance of playback with settings specifically for non-spatialized,
non-distance-attenuated sounds. Audio Components created using this function by default will not have Spatialization applied.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sound | Sound to create. |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far into the sound to begin playback at |
| object | Concurrency Settings | Override concurrency settings package to play sound with |
| boolean | Persist Across Level Transition |  |
| boolean | Auto Destroy | Whether the returned audio component will be automatically cleaned up when the sound finishes (by completing or stopping), or whether it can be reactivated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An audio component to manipulate the created sound |
