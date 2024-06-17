---
title: Set Mesh Triangle UVs
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Sets the UVs of a mesh triangle in the given UV Channel.
This function will create new UV elements for each vertex of the triangle, meaning that
the triangle will become an isolated UV island.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Triangle ID |  |
| struct | UVs |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Triangle |  |
| object | Target Mesh | Sets the UVs of a mesh triangle in the given UV Channel.This function will create new UV elements for each vertex of the triangle, meaning thatthe triangle will become an isolated UV island. |
