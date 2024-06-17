---
title: Make Musical Spectral Analysis Band Settings
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Analysis](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Analysis)

Make an array of musically spaced bands with ascending frequency.

Target is Audio Mixer Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | In Num Semitones | The number of semitones to represent. |
| enum | In Starting Musical Note |  |
| integer | In Starting Octave | The octave of the first note in the array. |
| integer | In Attack Time Msec | The attack time (in milliseconds) to apply to each band's envelope tracker. |
| integer | In Release Time Msec | The release time (in milliseconds) to apply to each band's envelope tracker. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value |  |
