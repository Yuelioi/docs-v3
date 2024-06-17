---
title: Create Circle Path 2D
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Path](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyPath)

Create a closed circle on the XY plane around the given Center.
By our convention for closed paths, the end vertex is *not* a duplicate of the start vertex.

Target is Geometry Script Library Poly Path Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector2d struct | Center |  |
| real | Radius |  |
| integer | Num Points |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Poly Path | Create a closed circle on the XY plane around the given Center.By our convention for closed paths, the end vertex is *not* a duplicate of the start vertex. |
