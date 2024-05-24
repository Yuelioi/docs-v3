---
display_name: Get Polygon Vertex Count
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Polygon List](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolygonList)

Returns the number of vertices in a Polygon's outer shape, if HoleIndex is -1, or in the specified inner hole.
Returns 0 for invalid Polygon or Hole indices.

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
| integer | Return Value | Returns the number of vertices in a Polygon's outer shape, if HoleIndex is -1, or in the specified inner hole.Returns 0 for invalid Polygon or Hole indices. |
