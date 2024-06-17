---
title: Get Section from Static Mesh
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Procedural Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh)

Grab geometry data from a StaticMesh asset.

Target is Kismet Procedural Mesh Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Mesh |  |
| integer | LODIndex |  |
| integer | Section Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Vertices |  |
| integer | Triangles |  |
| vector | Normals |  |
| vector2d struct | UVs |  |
| struct | Tangents |  |
