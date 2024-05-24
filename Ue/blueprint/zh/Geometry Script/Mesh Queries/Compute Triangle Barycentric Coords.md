---
display_name: Compute Triangle Barycentric Coords
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Compute the barycentric coordinates (A,B,C) of the Point relative to the specified TriangleID of the TargetMesh.
The properties of barycentric coordinates are such that A,B,C are all positive, A+B+C=1.0, and A*Vertex1 + B*Vertex2 + C\*Vertex3 = Point.
So, the barycentric coordinates can be used to smoothly interpolate/blend any other per-triangle-vertex quantities.
The Point must lie in the plane of the Triangle, otherwise the coordinates are somewhat meaningless (but clamped to 0-1 range to avoid catastrophic errors)
The Positions of the Triangle Vertices are also returned for convenience (similar to GetTrianglePositions)

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |
| vector | Point |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Triangle | will be returned true if TriangleID exists in TargetMesh, and otherwise will be returned false |
| vector | Vertex 1 |  |
| vector | Vertex 2 |  |
| vector | Vertex 3 |  |
| vector | Barycentric Coords |  |
| object | Target Mesh |  |
