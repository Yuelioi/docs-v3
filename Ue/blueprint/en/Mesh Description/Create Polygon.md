---
title: Create Polygon
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh Description](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshDescription)

Adds a new polygon to the mesh and returns its ID. This will also make any missing edges, and all constituent triangles.

Target is Mesh Description Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Polygon Group ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Vertex Instance IDs |  |
| struct | New Edge IDs |  |
| struct | Return Value | Adds a new polygon to the mesh and returns its ID. This will also make any missing edges, and all constituent triangles. |
