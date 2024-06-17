---
title: Update Mesh Section
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Procedural Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh)

Updates a section of this procedural mesh component. This is faster than CreateMeshSection, but does not let you change topology. Collision info is also updated.

Target is Procedural Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Section Index |  |
| vector | Vertices | Vertex buffer of all vertex positions to use for this mesh section. |
| vector | Normals | Optional array of normal vectors for each vertex. If supplied, must be same length as Vertices array. |
| vector2d struct | UV0 | Optional array of texture co-ordinates for each vertex. If supplied, must be same length as Vertices array. |
| vector2d struct | UV1 |  |
| vector2d struct | UV2 |  |
| vector2d struct | UV3 |  |
| linearcolor | Vertex Colors | Optional array of colors for each vertex. If supplied, must be same length as Vertices array. |
| struct | Tangents | Optional array of tangent vector for each vertex. If supplied, must be same length as Vertices array. |
| boolean | SRGB Conversion | Whether to do sRGB conversion when converting FLinearColor to FColor |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
