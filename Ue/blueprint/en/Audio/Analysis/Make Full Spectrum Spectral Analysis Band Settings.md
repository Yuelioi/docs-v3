---
display_name: Make Full Spectrum Spectral Analysis Band Settings
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Analysis](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Analysis)

Make an array of logarithmically spaced bands.

Target is Audio Mixer Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | In Num Bands | The number of bands to used to represent the spectrum. |
| real | In Minimum Frequency | The center frequency of the first band. |
| real | In Maximum Frequency | The center frequency of the last band. |
| integer | In Attack Time Msec | The attack time (in milliseconds) to apply to each band's envelope tracker. |
| integer | In Release Time Msec | The release time (in milliseconds) to apply to each band's envelope tracker. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value |  |
