---
display_name: Draw Border
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Draws a 3x3 grid border with tiled frame and tiled interior on the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Border Texture | Texture to use for border. |
| object | Background Texture | Texture to use for border background. |
| object | Left Border Texture | Texture to use for the tiling left border. |
| object | Right Border Texture | Texture to use for the tiling right border. |
| object | Top Border Texture | Texture to use for the tiling top border. |
| object | Bottom Border Texture | Texture to use for the tiling bottom border. |
| vector2d struct | Screen Position | Screen space position to render the texture. |
| vector2d struct | Screen Size | Screen space size to render the texture. |
| vector2d struct | Coordinate Position | Normalized UV starting coordinate to use when rendering the border texture. |
| vector2d struct | Coordinate Size | Normalized UV size coordinate to use when rendering the border texture. |
| linearcolor | Render Color | Color to tint the border. |
| vector2d struct | Border Scale | Scale of the border. |
| vector2d struct | Background Scale | Scale of the background. |
| real | Rotation | Rotation, in degrees, to render the texture. |
| vector2d struct | Pivot Point | Normalized pivot point to use when rotating the texture. |
| vector2d struct | Corner Size | Frame corner size in percent of frame texture (should be \< 0.5f). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
