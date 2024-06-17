---
title: Create Grid Mesh Split
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Procedural Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh)

Generate a vertex buffer, index buffer and UVs for a grid mesh where each quad is split, with standard 0-1 UVs on UV0 and point sampled texel center UVs for UV1.

Target is Kismet Procedural Mesh Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Num X | Number of vertices in X direction (must be >= 2) |
| integer | Num Y | Number of vertices in y direction (must be >= 2) |
| real | Grid Spacing | Size of each quad in world units |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Triangles |  |
| vector | Vertices |  |
| vector2d struct | UVs |  |
| vector2d struct | UV1s |  |
