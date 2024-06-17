---
title: Get All Split UVs at Vertex
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Returns the unique UV element IDs and values associated with the mesh vertex, in the specified UV Channel.
If the Vertex or UV channel does not exist, the arrays will be empty and bHaveValidUVs will be set to false.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Vertex ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Element IDs |  |
| vector2d struct | Element UVs |  |
| boolean | Have Valid UVs |  |
| object | Target Mesh | Returns the unique UV element IDs and values associated with the mesh vertex, in the specified UV Channel.If the Vertex or UV channel does not exist, the arrays will be empty and bHaveValidUVs will be set to false. |
