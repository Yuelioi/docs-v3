---
display_name: Unflatten Points
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Point Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PointSet)

Convert an array of points from 2D to 3D, by transforming out of the given ReferenceFrame, with the given Height for the non-flat axis (default Z).

Target is Geometry Script Library Point Set Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector2d struct | Points in 2D |  |
| struct | Options |  |
| real | Height |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Points in 3D |  |
