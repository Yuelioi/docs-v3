---
display_name: Approximate Convex Hulls with Simpler Collision Shapes
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Collision)

Attempt to approximate any convex hulls in the given simple collision representation. Updates the passed-in Simple Collision.
Convex hulls that aren't well approximated (to tolerances set in ApproximateOptions) will remain as convex hulls.

Target is Geometry Script Library Collision Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Simple Collision | The collision in which to attempt to approximate the convex hulls |
| struct | Approximate Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Has Approximated | Indicates whether any convex hulls were replaced with simpler approximations |
