---
title: Get Vector List Item
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [List Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/ListUtils)

Returns the FVector stored in the VectorList at the specified location.
if the Index is not valid for this Vector List, the Zero Vector will be returned and bIsValidIndex set to false.

Target is Geometry Script Library List Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Vector List |  |
| integer | Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Index |  |
| vector | Return Value | Returns the FVector stored in the VectorList at the specified location.if the Index is not valid for this Vector List, the Zero Vector will be returned and bIsValidIndex set to false. |
