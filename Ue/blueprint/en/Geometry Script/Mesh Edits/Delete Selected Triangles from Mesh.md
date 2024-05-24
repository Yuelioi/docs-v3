---
display_name: Delete Selected Triangles from Mesh
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Removes specified triangles, identified by mesh selection, from the mesh.
On return, NumDeleted will contain the actual number of triangles removed.

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Num Deleted |  |
| object | Target Mesh | Removes specified triangles, identified by mesh selection, from the mesh.On return, NumDeleted will contain the actual number of triangles removed. |
