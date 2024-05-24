---
display_name: Merge Simple Collision Shapes
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Collision)

Attempt to merge collision shapes to create a representation with fewer overall shapes.

Target is Geometry Script Library Collision Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Simple Collision | The collision to attempt to simplify by merging shapes |
| struct | Merge Options | Options controlling how shapes can be merged |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Has Merged | Indicates whether any shapes have been merged |
| struct | Merged Simple Collision | Simple Collision with collision shapes merged, as allowed by settings |
