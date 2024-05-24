---
display_name: Set Wave Scalar
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

Set a temporal wave scalar value according to the sample distance from the field position.

Target is Wave Scalar

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Field Magnitude | Magnitude of the wave function |
| vector | Center Position | Center position of the wave field |
| real | Wave Length | Distance between 2 wave peaks |
| real | Wave Period | Time over which the wave will travel from one peak to another one. The wave velocity is proportional to wavelength/period |
| enum | Wave Function | Wave function used for the field |
| enum | Falloff Type | Type of falloff function used if the falloff function is picked |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
