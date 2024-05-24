---
display_name: Get Simple Polygon
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Polygon List](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolygonList)

Returns a specified Simple Polygon from a Polygon List -- either the outer polygon, if HoleIndex is -1, or specified inner hole.
Polygon will be empty for invalid Polygon or Hole indices.

Target is Geometry Script Library Polygon List Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Polygon List |  |
| integer | Polygon Index |  |
| integer | Hole Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Valid Indices |  |
| struct | Return Value | Returns a specified Simple Polygon from a Polygon List -- either the outer polygon, if HoleIndex is -1, or specified inner hole.Polygon will be empty for invalid Polygon or Hole indices. |
