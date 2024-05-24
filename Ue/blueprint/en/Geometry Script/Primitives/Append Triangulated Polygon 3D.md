---
display_name: Append Triangulated Polygon 3D
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

Appends a Triangulated Polygon (with vertices specified in 3D) to the Target Mesh.
Uses Ear Clipping-based triangulation. Output vertices will always be 1:1 with input vertices.
Polygon endpoint is not repeated.

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| vector | Polygon Vertices 3D |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Appends a Triangulated Polygon (with vertices specified in 3D) to the Target Mesh.Uses Ear Clipping-based triangulation. Output vertices will always be 1:1 with input vertices.Polygon endpoint is not repeated. |
