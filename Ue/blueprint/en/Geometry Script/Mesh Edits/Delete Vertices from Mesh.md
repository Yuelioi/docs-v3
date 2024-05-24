---
display_name: Delete Vertices from Mesh
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Removes a list of vertices from the mesh.
On return, NumDeleted will contain the actual number of vertices removed.

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Vertex List |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Num Deleted |  |
| object | Target Mesh | Removes a list of vertices from the mesh.On return, NumDeleted will contain the actual number of vertices removed. |
