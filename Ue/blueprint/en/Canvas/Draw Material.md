---
display_name: Draw Material
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Draws a material on the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Material | Material to use when rendering. Remember that only the emissive channel is able to be rendered as no lighting is performed when rendering to the Canvas. |
| vector2d struct | Screen Position | Screen space position to render the texture. |
| vector2d struct | Screen Size | Screen space size to render the texture. |
| vector2d struct | Coordinate Position | Normalized UV starting coordinate to use when rendering the texture. |
| vector2d struct | Coordinate Size | Normalized UV size coordinate to use when rendering the texture. |
| real | Rotation | Rotation, in degrees, to render the texture. |
| vector2d struct | Pivot Point | Normalized pivot point to use when rotating the texture. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
