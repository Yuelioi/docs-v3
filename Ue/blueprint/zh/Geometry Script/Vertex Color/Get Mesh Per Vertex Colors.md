---
display_name: Get Mesh Per Vertex Colors
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Vertex Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/VertexColor)

Get a list of single vertex colors for each mesh vertex in the TargetMesh, derived from the VertexColor Overlay.
The VertexColor Overlay may store multiple colors for a single vertex (ie different colors for that vertex on different triangles)
In such cases the colors can either be averaged, or the last color seen will be used, depending on the bBlendSplitVertexValues parameter.

Target is Geometry Script Library Mesh Vertex Color Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| boolean | Blend Split Vertex Values | control how multiple colors at the same vertex should be interpreted |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Color List | output color list will be stored here. Size will be equal to the MaxVertexID of TargetMesh (not the VertexCount!) |
| boolean | Is Valid Color Set | will be set to true if the VertexColor Overlay was valid |
| boolean | Has Vertex IDGaps | will be set to true if some vertex indices in TargetMesh were invalid, ie MaxVertexID > VertexCount |
| object | Target Mesh |  |
