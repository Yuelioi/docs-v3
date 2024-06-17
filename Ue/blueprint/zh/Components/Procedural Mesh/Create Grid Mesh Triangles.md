---
title: Create Grid Mesh Triangles
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Procedural Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh)

Generate an index buffer for a grid of quads.

Target is Kismet Procedural Mesh Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Num X | Number of vertices in X direction (must be >= 2) |
| integer | Num Y | Number of vertices in y direction (must be >= 2) |
| boolean | Winding | Reverses winding of indices generated for each quad |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Triangles |  |
