---
display_name: Append Cylinder
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

Appends a 3D Cylinder (with optional end caps) to the Target Mesh.

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| real | Radius |  |
| real | Height |  |
| integer | Radial Steps |  |
| integer | Height Steps |  |
| boolean | Capped |  |
| enum | Origin |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Appends a 3D Cylinder (with optional end caps) to the Target Mesh. |
