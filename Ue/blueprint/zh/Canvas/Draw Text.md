---
display_name: Draw Text
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Draws text on the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Font | Font to use when rendering the text. If this is null, then a default engine font is used. |
| string | Render Text | Text to render on the Canvas. |
| vector2d struct | Screen Position | Screen space position to render the text. |
| vector2d struct | Scale |  |
| linearcolor | Render Color | Color to render the text. |
| real | Kerning | Horizontal spacing adjustment to modify the spacing between each letter. |
| linearcolor | Shadow Color | Color to render the shadow of the text. |
| vector2d struct | Shadow Offset | Pixel offset relative to the screen space position to render the shadow of the text. |
| boolean | Centre X | If true, then interpret the screen space position X coordinate as the center of the rendered text. |
| boolean | Centre Y | If true, then interpret the screen space position Y coordinate as the center of the rendered text. |
| boolean | Outlined | If true, then the text should be rendered with an outline. |
| linearcolor | Outline Color | Color to render the outline for the text. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
