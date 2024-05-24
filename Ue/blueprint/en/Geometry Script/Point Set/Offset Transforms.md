---
display_name: Offset Transforms
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Point Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PointSet)

Offset the location of all Transforms by Offset in the given Direction, either locally in the space of the transform or in world space.
For example, this can offset mesh surface samples along the surface normal direction.

Target is Geometry Script Library Point Set Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| transform | Transforms |  |
| real | Offset |  |
| vector | Direction |  |
| enum | Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
