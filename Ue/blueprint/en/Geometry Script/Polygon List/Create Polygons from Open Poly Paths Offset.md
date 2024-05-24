---
display_name: Create Polygons from Open Poly Paths Offset
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Polygon List](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolygonList)

Apply an offset to a set of open 2D PolyPaths, generating closed polygons as a result

Target is Geometry Script Library Polygon List Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Poly Paths |  |
| struct | Offset Options |  |
| real | Offset |  |
| boolean | Copy Input on Failure |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Operation Success |  |
| struct | Return Value | Apply an offset to a set of open 2D PolyPaths, generating closed polygons as a result |
