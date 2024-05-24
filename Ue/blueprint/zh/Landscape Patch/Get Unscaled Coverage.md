---
display_name: Get Unscaled Coverage
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape Patch](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LandscapePatch)

Gives size in unscaled world coordinates (ie before applying patch transform) of the patch as measured
between the centers of the outermost pixels. Measuring the coverage this way means that a patch can
affect the same region of the landscape regardless of patch resolution.
This is also the range across which bilinear interpolation always has correct values, so the area outside
this center portion is usually set as a "dead" border that doesn't affect the landscape.

Target is Landscape Texture Patch

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | Gives size in unscaled world coordinates (ie before applying patch transform) of the patch as measuredbetween the centers of the outermost pixels. Measuring the coverage this way means that a patch canaffect the same region of the landscape regardless of patch resolution.This is also the range across which bilinear interpolation always has correct values, so the area outsidethis center portion is usually set as a "dead" border that doesn't affect the landscape. |
