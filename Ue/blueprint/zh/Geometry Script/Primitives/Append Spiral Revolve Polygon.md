---
display_name: Append Spiral Revolve Polygon
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

Revolves a 2D polygon on a helical path, like one used to create a vertical spiral, appending the result to the Target Mesh.

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| vector2d struct | Polygon Vertices |  |
| struct | Revolve Options |  |
| real | Radius |  |
| integer | Steps |  |
| real | Rise Per Revolution |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Revolves a 2D polygon on a helical path, like one used to create a vertical spiral, appending the result to the Target Mesh. |
