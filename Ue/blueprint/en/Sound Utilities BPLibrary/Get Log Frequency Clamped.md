---
display_name: Get Log Frequency Clamped
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sound Utilities BPLibrary](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SoundUtilitiesBPLibrary)

Returns the log frequency of the input value. Maps linear domain and range values to log output (good for linear slider controlling frequency)

Target is Sound Utilities BPFunction Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | In Value | The linear value to convert to logarithmic frequency |
| vector2d struct | In Domain | The domain to use when converting between linear and logarithmic scales |
| vector2d struct | In Range | The range to use when converting between linear and logarithmic scales |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | The log frequency of the given input |
