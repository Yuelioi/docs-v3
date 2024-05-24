---
display_name: Get Polygon Internal Edges
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh Description](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshDescription)

Populate the provided array with a list of edges which are internal to the polygon, i.e. those which separate
constituent triangles.

Target is Mesh Description Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Polygon ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Edge IDs |  |
