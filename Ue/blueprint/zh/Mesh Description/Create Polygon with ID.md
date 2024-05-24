---
display_name: Create Polygon with ID
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh Description](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshDescription)

Adds a new polygon to the mesh with the given ID. This will also make any missing edges, and all constituent triangles.

Target is Mesh Description Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Polygon ID |  |
| struct | Polygon Group ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Vertex Instance IDs |  |
| struct | New Edge IDs |  |
