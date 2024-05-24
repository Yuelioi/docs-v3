---
display_name: Draw Texture
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Draws a texture on the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Texture | Texture to use when rendering. If no texture is set then this will use the default white texture. |
| vector2d struct | Screen Position | Screen space position to render the texture. |
| vector2d struct | Screen Size | Screen space size to render the texture. |
| vector2d struct | Coordinate Position | Normalized UV starting coordinate to use when rendering the texture. |
| vector2d struct | Coordinate Size | Normalized UV size coordinate to use when rendering the texture. |
| linearcolor | Render Color | Color to use when rendering the texture. |
| enum | Blend Mode | Blending mode to use when rendering the texture. |
| real | Rotation | Rotation, in degrees, to render the texture. |
| vector2d struct | Pivot Point | Normalized pivot point to use when rotating the texture. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
