---
title: Get Closest Point on Collision
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Returns the distance and closest point to the collision surface.
Component must have simple collision to be queried for closest point.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | Point | World 3D vector |
| name | Bone Name | If a SkeletalMeshComponent, name of body to set center of mass of. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Point on Body | Point on the surface of collision closest to Point |
| real | Return Value | Success if returns > 0.f, if returns 0.f, it is either not convex or inside of the point If returns \< 0.f, this primitive does not have collsion |
