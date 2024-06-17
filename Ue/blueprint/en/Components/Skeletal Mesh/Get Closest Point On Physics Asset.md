---
title: Get Closest Point On Physics Asset
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skeletal Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkeletalMesh)

Given a world position, find the closest point on the physics asset. Note that this is independent of collision and welding. This is based purely on animation position

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | World Position | The point we want the closest point to (i.e. for all bodies in the physics asset, find the one that has a point closest to WorldPosition) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Closest World Position |  |
| vector | Normal |  |
| name | Bone Name |  |
| real | Distance |  |
| boolean | Return Value | true if we found a closest point |
