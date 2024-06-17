---
title: Get UVList Item
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [List Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/ListUtils)

Returns the FVector2D stored in the UV List at the specified location.
If the Index is not valid for this UV List, the Zero Vector will be returned and bIsValidIndex set to false.

Target is Geometry Script Library List Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | UVList |  |
| integer | Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Index |  |
| vector2d struct | Return Value | Returns the FVector2D stored in the UV List at the specified location.If the Index is not valid for this UV List, the Zero Vector will be returned and bIsValidIndex set to false. |
