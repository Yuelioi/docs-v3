---
title: Generate Cylindrical UVChannel
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Generates cylindrical UV mapping in the specified UV channel on the given LOD of a StaticMesh.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Static mesh on which to generate the UV mapping. |
| integer | LODIndex | Index of the StaticMesh LOD. |
| integer | UVChannel Index | Channel where to save the UV mapping. |
| vector | Position | Position of the center of the projection gizmo. |
| rotator | Orientation | Rotation to apply to the projection gizmo. |
| vector2d struct | Tiling | The UV tiling to use to generate the UV mapping. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the UV mapping was generated. |
