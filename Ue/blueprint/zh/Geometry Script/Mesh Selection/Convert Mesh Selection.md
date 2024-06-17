---
title: Convert Mesh Selection
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Convert a Mesh Selection to a different Type (eg Vertices to Triangles, etc)
By default, Vertices map to Triangle one-rings, and Triangles to all contained vertices.
If bAllowPartialInclusion is disabled, then more restrictive conversions are performed, as follows:
For To-Vertices, only include vertices where all one-ring triangles are included in FromSelection.
For To-Triangles, only include triangles where all tri vertices are included in FromSelection.
For To-PolyGroups, only include groups where all group triangles are included in FromSelection

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | From Selection |  |
| enum | New Type |  |
| boolean | Allow Partial Inclusion | if false, perform more limited selection conversion as described above |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | To Selection |  |
| object | Target Mesh |  |
