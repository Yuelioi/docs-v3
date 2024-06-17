---
title: Simplify Convex Hulls
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Collision)

Simplify any convex hulls in the given simple collision representation. Updates the passed-in Simple Collision.

Target is Geometry Script Library Collision Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Simple Collision | The collision in which to attempt to simplify the convex hulls |
| struct | Simplify Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Has Simplified | Indicates whether any convex hulls were modified |
