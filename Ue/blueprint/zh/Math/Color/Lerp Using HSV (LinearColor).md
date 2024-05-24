---
display_name: Lerp Using HSV (LinearColor)
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Color)

Linearly interpolates between two colors by the specified Alpha amount (100% of A when Alpha=0 and 100% of B when Alpha=1). The interpolation is performed in HSV color space taking the shortest path to the new color's hue. This can give better results than a normal lerp, but is much more expensive. The incoming colors are in RGB space, and the output color will be RGB. The alpha value will also be interpolated.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| linearcolor | A | The color and alpha to interpolate from as linear RGBA |
| linearcolor | B | The color and alpha to interpolate to as linear RGBA |
| real | Alpha | Scalar interpolation amount (usually between 0.0 and 1.0 inclusive) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| linearcolor | Return Value | The interpolated color in linear RGB space along with the interpolated alpha value |
