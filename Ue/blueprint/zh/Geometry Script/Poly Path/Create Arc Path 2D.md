---
display_name: Create Arc Path 2D
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Path](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyPath)

Create an open arc on the XY plane around the given Center.
As it is an open path, the end vertex exactly hits the target EndAngle (so will be positioned on the start vertex if the end aligns to the start)

Target is Geometry Script Library Poly Path Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector2d struct | Center |  |
| real | Radius |  |
| integer | Num Points |  |
| real | Start Angle |  |
| real | End Angle |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Poly Path | Create an open arc on the XY plane around the given Center.As it is an open path, the end vertex exactly hits the target EndAngle (so will be positioned on the start vertex if the end aligns to the start) |
