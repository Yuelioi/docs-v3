---
title: Get Actor Bounds
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Returns the bounding box of all components that make up this Actor (excluding ChildActorComponents).

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Only Colliding Components | If true, will only return the bounding box for components with collision enabled. |
| boolean | Include from Child Actors | If true then recurse in to ChildActor components |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Origin | Set to the center of the actor in world space |
| vector | Box Extent | Set to half the actor's size in 3d space |
