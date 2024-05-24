---
display_name: Generate Box Mesh
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Procedural Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh)

Generate vertex and index buffer for a simple box, given the supplied dimensions. Normals, UVs and tangents are also generated for each vertex.

Target is Kismet Procedural Mesh Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Box Radius |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Vertices |  |
| integer | Triangles |  |
| vector | Normals |  |
| vector2d struct | UVs |  |
| struct | Tangents |  |
