---
title: Wrapped Text Size
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Returns the wrapped text size in screen space coordinates.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Font | Font to use when determining the size of the text. If this is null, then a default engine font is used. |
| string | Render Text | Text to determine the size of. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector2d struct | Return Value | Returns the screen space size of the text. |
