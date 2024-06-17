---
title: Add Spectral Analysis Delegate
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Spectrum](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Spectrum)

Adds a spectral analysis delegate to receive notifications when this submix has spectrum analysis enabled.

Target is Sound Submix

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Band Settings | The frequency bands to analyze and their envelope-following settings. |
| delegate | On Submix Spectral Analysis BP | Event to fire when new spectral data is available. |
| real | Update Rate | How often to retrieve the data from the spectral analyzer and broadcast the event. Max is 30 times per second. |
| real | Decibel Noise Floor | Decibel Noise Floor to consider as silence when using a Decibel Spectrum Type. |
| boolean | Do Normalize | If true, output band values will be normalized between zero and one. |
| boolean | Do Auto Range | If true, output band values will have their ranges automatically adjusted to the minimum and maximum values in the audio. Output band values will be normalized between zero and one. |
| real | Auto Range Attack Time | The time (in seconds) it takes for the range to expand to 90% of a larger range. |
| real | Auto Range Release Time | The time (in seconds) it takes for the range to shrink to 90% of a smaller range. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
