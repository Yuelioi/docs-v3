---
title: Get Poly Path Vertex
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Path](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyPath)

Returns the 3D position of the requested vertex in the PolyPath.
If the Index does not correspond to a vertex in the PolyPath, a Zero Vector (0,0,0) will be returned.

Target is Geometry Script Library Poly Path Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Poly Path |  |
| integer | Index | specifies a vertex in the PolyPath. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Index | will be false on return if the Index is not included in the PolyPath. |
| vector | Return Value |  |
