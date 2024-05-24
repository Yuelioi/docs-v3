---
display_name: Min Area Rectangle
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Geometry)

Finds the minimum area rectangle that encloses a set of coplanar points.
Uses the exhaustive search algorithm in http://www.geometrictools.com/Documentation/MinimumAreaRectangle.pdf

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | In Points | Points to enclose in the rectangle; need to be within the same plane for correct results |
| vector | Sample Surface Normal | Normal indicating the surface direction for the points |
| boolean | Debug Draw | Draws the output rectangle for debugging purposes provided the world context is set as well |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Rect Center | Translation for the output rectangle from the origin |
| rotator | Out Rect Rotation | Rotation for the output rectangle from the XY plane |
| real | Out Rect Length X | Length of the output rectangle along the X axis before rotation |
| real | Out Rect Length Y | Length of the output rectangle along the Y axis before rotation |
