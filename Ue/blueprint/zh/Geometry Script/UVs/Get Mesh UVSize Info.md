---
title: Get Mesh UVSize Info
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Compute information about dimensions and areas for a UV Set of a Mesh, with an optional Mesh Selection

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel | index of UV Channel to query |
| struct | Selection | subset of triangles to process, whole mesh is used if selection is not provided |
| boolean | Only Include Valid UVTris | if true, only triangles with valid UVs are included in 3D Mesh Area/Bounds |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Mesh Area | output 3D area of queried triangles |
| real | UVArea | output 2D UV-space area of queried triangles |
| struct | Mesh Bounds | output 3D bounding box of queried triangles |
| struct | UVBounds | output 2D UV-space bounding box of queried triangles |
| boolean | Is Valid UVSet | output flag set to false if UV Channel does not exist on the target mesh. In this case Areas and Bounds are not initialized. |
| boolean | Found Unset UVs | output flag set to true if any of the queried triangles do not have valid UVs set |
| object | Copy from Mesh |  |
