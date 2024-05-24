---
display_name: Append Mesh
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Apply Append Transform to Append Mesh and then add its geometry to the Target Mesh.

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Append Mesh |  |
| transform | Append Transform |  |
| boolean | Defer Change Notifications |  |
| struct | Append Options | Control how details like mesh attributes are handled when one mesh is appended to another. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
