---
title: Create Face Mesh
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [ARFace Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ARFaceMesh)

Create the initial face mesh from raw mesh data

Target is Apple ARKit Face Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Vertices | Vertex buffer of all vertex positions to use for this mesh section. |
| integer | Triangles | Index buffer indicating which vertices make up each triangle. Length must be a multiple of 3. |
| vector2d struct | UV0 | Optional array of texture co-ordinates for each vertex. If supplied, must be same length as Vertices array. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
