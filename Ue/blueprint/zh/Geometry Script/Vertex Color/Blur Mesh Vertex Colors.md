---
display_name: Blur Mesh Vertex Colors
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Vertex Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/VertexColor)

Blur the color attribute of the mesh. If the mesh has no color attribute, the function returns the mesh unchanged.

Target is Geometry Script Library Mesh Vertex Color Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | The mesh containing the color attribute. |
| struct | Selection | Only vertices in the selection will have their color attribute blurred. |
| integer | Num Iterations | The number of blur iterations. |
| real | Strength | Each iteration, we will blur between the vertex of the color at the previous iteration and its neighbors' average by Strength amount (expected to be in the zero to one range). |
| enum | Blur Mode | Determines how neighbors are weighted when computing their average. |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
