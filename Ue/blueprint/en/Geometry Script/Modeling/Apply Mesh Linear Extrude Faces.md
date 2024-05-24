---
display_name: Apply Mesh Linear Extrude Faces
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Modeling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Modeling)

Apply Linear Extrusion (ie extrusion in a single direction) to the triangles of TargetMesh identified by the Selection.
The input Selection will still identify the same geometric elements after the Extrusion

Target is Geometry Script Library Mesh Modeling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| struct | Selection |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Apply Linear Extrusion (ie extrusion in a single direction) to the triangles of TargetMesh identified by the Selection.The input Selection will still identify the same geometric elements after the Extrusion |
