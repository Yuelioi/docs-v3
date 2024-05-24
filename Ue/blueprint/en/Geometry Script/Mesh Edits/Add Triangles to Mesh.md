---
display_name: Add Triangles to Mesh
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Adds a list of triangles to the mesh and populates the New Indices List with the corresponding new Triangle IDs.

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | New Triangles List |  |
| integer | New Triangle Group ID |  |
| boolean | Defer Change Notifications |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Indices List |  |
| object | Target Mesh | Adds a list of triangles to the mesh and populates the New Indices List with the corresponding new Triangle IDs. |
