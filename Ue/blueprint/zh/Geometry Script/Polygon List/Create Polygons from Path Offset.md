---
title: Create Polygons from Path Offset
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Polygon List](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolygonList)

Apply an offset to a single open 2D path, generating closed polygons as a result

Target is Geometry Script Library Polygon List Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector2d struct | Path |  |
| struct | Offset Options |  |
| real | Offset |  |
| boolean | Copy Input on Failure |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Operation Success |  |
| struct | Return Value | Apply an offset to a single open 2D path, generating closed polygons as a result |
