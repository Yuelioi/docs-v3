---
display_name: Append Delaunay Triangulation 2D
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

Generates a Delaunay Triangulation of the provided vertices, and appends it to the Target Mesh.
If optional Constrained Edges are provided, will generate a Constrained Delaunay Triangulation which connects the specified vertices with edges.
On success, all vertices are always appended to the output mesh, though duplicate vertices will not be used in any triangles and may optionally be removed.
Use PositionsToVertexIDs to map indices in the input VertexPositions array to vertex IDs in the Dynamic Mesh.

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| vector2d struct | Vertex Positions |  |
| struct | Constrained Edges |  |
| struct | Triangulation Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Positions to Vertex IDs |  |
| boolean | Has Duplicate Vertices |  |
| object | Target Mesh | Generates a Delaunay Triangulation of the provided vertices, and appends it to the Target Mesh.If optional Constrained Edges are provided, will generate a Constrained Delaunay Triangulation which connects the specified vertices with edges.On success, all vertices are always appended to the output mesh, though duplicate vertices will not be used in any triangles and may optionally be removed.Use PositionsToVertexIDs to map indices in the input VertexPositions array to vertex IDs in the Dynamic Mesh. |
