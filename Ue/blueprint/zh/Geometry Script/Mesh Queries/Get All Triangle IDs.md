---
display_name: Get All Triangle IDs
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Returns an Index List of all Triangle IDs in a mesh.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Triangle IDList |  |
| boolean | Has Triangle IDGaps | will be true on return if there are breaks in the sequential numeration of Triangle IDs, as would happen after deleting triangles. |
| object | Target Mesh |  |
