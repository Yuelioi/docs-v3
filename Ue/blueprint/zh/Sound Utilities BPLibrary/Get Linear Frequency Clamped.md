---
title: Get Linear Frequency Clamped
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sound Utilities BPLibrary](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SoundUtilitiesBPLibrary)

Returns the linear frequency of the input value. Maps log domain and range values to linear output (good for linear
slider representation/visualization of log frequency). Reverse of GetLogFrequencyClamped.

Target is Sound Utilities BPFunction Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | In Value | The logarithmic value to convert to linear frequency |
| vector2d struct | In Domain | The domain to use when converting between linear and logarithmic scales |
| vector2d struct | In Range | The range to use when converting between linear and logarithmic scales |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | The linear frequency of the given logarithmic input |
