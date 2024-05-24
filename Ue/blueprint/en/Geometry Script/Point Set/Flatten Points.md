---
display_name: Flatten Points
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Point Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PointSet)

Convert an array of points from 3D to 2D, by transforming into the given ReferenceFrame and taking the X,Y coordinates
Note that to transform into the ReferenceFrame, we apply the inverse of the ReferenceFrame's transform.

Target is Geometry Script Library Point Set Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Points in 3D |  |
| struct | Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector2d struct | Points in 2D |  |
