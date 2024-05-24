---
display_name: Delete Triangle from Mesh
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Removes a triangle from the mesh as indicated by the Triangle ID.
Should the delete fail, e.g. if the specified triangle was not a mesh element, the flag bWasTriangleDelete will be set to false.

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Was Triangle Deleted |  |
| object | Target Mesh | Removes a triangle from the mesh as indicated by the Triangle ID.Should the delete fail, e.g. if the specified triangle was not a mesh element, the flag bWasTriangleDelete will be set to false. |
