---
display_name: Draw Line
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Painting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Painting)

Draws a line.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Context |  |
| vector2d struct | Position A | Starting position of the line in local space. |
| vector2d struct | Position B | Ending position of the line in local space. |
| linearcolor | Tint | Color to render the line. |
| boolean | Anti Alias | Whether the line should be antialiased. |
| real | Thickness | How many pixels thick this line should be. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
