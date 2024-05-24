---
display_name: Set Control Bus Mix By Filter
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Sets filtered stages of a given class to a provided target value for active instance of mix.
Does not update UObject definition of mix.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Mix | Mix to modify |
| string | Address Filter | (Optional) Address filter to apply to provided mix's stages. |
| class | Param Class Filter | (Optional) Filters buses by parameter class. |
| object | Param Filter | (Optional) Filters buses by parameter. |
| real | Value | Target value to mix filtered stages to. |
| real | Fade Time | If non-negative, updates the fade time for the resulting bus stages found matching the provided filter. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
