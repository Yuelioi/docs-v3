---
display_name: Get Columns to Exclude
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Object Mixer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ObjectMixer)

Specify a list of property names corresponding to columns you don't want to ever show.
For example, you can specify "Intensity" and "LightColor" to ensure that they can't be enabled or shown in the UI.
Columns not specified can be enabled by the user in the UI.

Target is Object Mixer Blueprint Object Filter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | Specify a list of property names corresponding to columns you don't want to ever show.For example, you can specify "Intensity" and "LightColor" to ensure that they can't be enabled or shown in the UI.Columns not specified can be enabled by the user in the UI. |
