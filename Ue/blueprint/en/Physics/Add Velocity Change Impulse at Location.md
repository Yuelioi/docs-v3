---
title: Add Velocity Change Impulse at Location
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Add an impulse to a single rigid body at a specific location. The Strength is taken as a change in angular velocity instead of an impulse (ie. mass will have no effect).

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Impulse | Magnitude and direction of impulse to apply. |
| vector | Location | Point in world space to apply impulse at. |
| name | Bone Name | If a SkeletalMeshComponent, name of bone to apply impulse to. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
