---
title: ComputePolyGroupsFromAngleThreshold
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Groups](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyGroups)

Sets PolyGroups by partitioning the mesh based on an edge crease/opening-angle.
Note, this will have no effect if the Group Layer does not exist.

Target is Geometry Script Library Mesh Polygroup Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Group Layer | indicates the PolyGroup Layer that will be populated. |
| real | Crease Angle | measured in degrees and used when comparing adjacent faces. |
| integer | Min Group Size | the minimum number of triangles in each PolyGroup. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
