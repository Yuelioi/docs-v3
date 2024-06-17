---
title: Create Triangle with ID
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh Description](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshDescription)

Adds a new triangle to the mesh with the given ID. This will also make an encapsulating polygon, and any missing edges.

Target is Mesh Description Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Triangle ID |  |
| struct | Polygon Group ID |  |
| struct | Vertex Instance IDs |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Edge IDs |  |
