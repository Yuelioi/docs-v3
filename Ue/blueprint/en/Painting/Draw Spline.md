---
display_name: Draw Spline
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Painting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Painting)

Draws a hermite spline.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Context |  |
| vector2d struct | Start | Starting position of the spline in local space. |
| vector2d struct | Start Dir | The direction of the spline from the start point. |
| vector2d struct | End | Ending position of the spline in local space. |
| vector2d struct | End Dir | The direction of the spline to the end point. |
| linearcolor | Tint | Color to render the spline. |
| real | Thickness | How many pixels thick this spline should be. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
