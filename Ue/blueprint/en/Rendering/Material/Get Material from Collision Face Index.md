---
title: Get Material from Collision Face Index
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Try and retrieve the material applied to a particular collision face of mesh. Used with face index returned from collision trace.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Face Index | Face index from hit result that was hit by a trace |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Section Index | Section of the mesh that the face belongs to |
| object | Return Value | Material applied to section that the hit face belongs to |
