---
title: Compute Negative Space
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Collision)

Compute the negative space of an input mesh surface that should be protected when merging simple collision shapes

Target is Geometry Script Library Collision Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Mesh BVH | A Dynamic Mesh BVH structure of the surface for which we will compute negative space |
| struct | Negative Space Options | Options controlling how the negative space is generated |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Negative Space | A set of spheres that cover the negative space of the input shape |
