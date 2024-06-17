---
title: Add Impulse
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Add an impulse to a single rigid body. Good for one time instant burst.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Impulse | Magnitude and direction of impulse to apply. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to apply impulse to. 'None' indicates root body. |
| boolean | Vel Change | If true, the Strength is taken as a change in velocity instead of an impulse (ie. mass will have no effect). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
