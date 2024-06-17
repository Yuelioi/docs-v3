---
title: Draw Polygon
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Draws a polygon on the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Texture | Texture to use when rendering the triangles. If no texture is set, then the default white texture is used. |
| vector2d struct | Screen Position | Screen space position to render the text. |
| vector2d struct | Radius | How large in pixels this polygon should be. |
| integer | Number Of Sides | How many sides this polygon should have. This should be above or equal to three. |
| linearcolor | Render Color | Color to tint the polygon. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
