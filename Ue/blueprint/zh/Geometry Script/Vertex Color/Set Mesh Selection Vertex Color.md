---
display_name: Set Mesh Selection Vertex Color
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Vertex Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/VertexColor)

Set the colors in the TargetMesh VertexColor Overlay identified by the Selection to a constant value.
For a Vertex Selection, each existing VertexColor Overlay Element for the vertex is updated.
For a Triangle or PolyGroup Selection, all Overlay Elements in the identified Triangles are updated.

Target is Geometry Script Library Mesh Vertex Color Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| linearcolor | Color | the constant color to set |
| struct | Flags | specify which RGBA channels to set (default all channels) |
| boolean | Create Color Seam | if true, a "hard edge" in the vertex colors is created, by creating new Elements for all the triangles in the selection. If enabled, Vertex selections are converted to Triangle selections, and Flags is ignored. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
