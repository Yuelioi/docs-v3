---
display_name: Apply Mesh Mirror
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Booleans](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Booleans)

Mirrors a mesh across a plane, with optional cutting and welding of triangles.

Target is Geometry Script Library Mesh Boolean Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | Dynamic Mesh to be updated by the mirror operation. |
| transform | Mirror Frame | defines the plane used to mirror the TargetMesh. |
| struct | Options | selects additional clean-up operations performed after the mirror. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
