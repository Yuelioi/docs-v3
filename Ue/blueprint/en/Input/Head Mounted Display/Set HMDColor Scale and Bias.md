---
display_name: Set HMDColor Scale and Bias
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

Multiply the post-compositor frame by a color and add a bias.
LayerColor = LayerColor * ColorScale + ColorBias

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| linearcolor | Color Scale | (in) Color to multiply the compositor layer by |
| linearcolor | Color Bias | (in) Color to offset the compositor layer by |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | (boolean) True if successful, false if unsuccessful or unsupported. |
