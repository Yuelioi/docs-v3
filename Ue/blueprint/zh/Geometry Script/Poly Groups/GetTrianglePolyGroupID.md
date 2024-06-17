---
title: GetTrianglePolyGroupID
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Groups](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyGroups)

Gets the PolyGroup ID associated with the specified Triangle ID and stored in the Group Layer.
If the Group Layer or the Triangle does not exist, the value 0 will be returned and bIsValidTriangle set to false.

Target is Geometry Script Library Mesh Polygroup Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |
| struct | Group Layer | indicates the layer on the Target Mesh to query. |
| integer | Triangle ID | identifies a triangle in the Target Mesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Triangle | will be populated on return with false if either the Group Layer or the Triangle does not exist. |
| integer | Poly Group ID |  |
