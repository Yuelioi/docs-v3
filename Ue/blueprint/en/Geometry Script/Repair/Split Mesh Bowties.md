---
title: Split Mesh Bowties
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Repair](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Repair)

Splits Bowties in the mesh and/or the attributes. A Bowtie is formed when a single vertex is connected to more than two boundary edges,
and splitting duplicates the shared vertex so each triangle will have a unique copy.

Target is Geometry Script Library Mesh Repair Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| boolean | Mesh Bowties |  |
| boolean | Attribute Bowties |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Splits Bowties in the mesh and/or the attributes. A Bowtie is formed when a single vertex is connected to more than two boundary edges,and splitting duplicates the shared vertex so each triangle will have a unique copy. |
