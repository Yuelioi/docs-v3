---
title: Make Preset Spectral Analysis Band Settings
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Analysis](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Analysis)

Make an array of bands which span the frequency range of a given EAudioSpectrumBandPresetType.

Target is Audio Mixer Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| enum | In Band Preset Type | The type audio content which the bands encompass. |
| integer | In Num Bands | The number of bands used to represent the spectrum. |
| integer | In Attack Time Msec | The attack time (in milliseconds) to apply to each band's envelope tracker. |
| integer | In Release Time Msec | The release time (in milliseconds) to apply to each band's envelope tracker. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value |  |
