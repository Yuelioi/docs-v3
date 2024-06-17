---
title: Create Arc Path 3D
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Path](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyPath)

Create an open arc around the origin on the XY plane, then transformed by Transform.
As it is an open path, the end vertex exactly hits the target EndAngle (so will be positioned on the start vertex if the end aligns to the start)

Target is Geometry Script Library Poly Path Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| transform | Transform |  |
| real | Radius |  |
| integer | Num Points |  |
| real | Start Angle |  |
| real | End Angle |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Poly Path | Create an open arc around the origin on the XY plane, then transformed by Transform.As it is an open path, the end vertex exactly hits the target EndAngle (so will be positioned on the start vertex if the end aligns to the start) |
