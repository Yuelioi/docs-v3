---
title: Add Torque in Degrees
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Add a torque to a single rigid body.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Torque | Torque to apply. Direction is axis of rotation and magnitude is strength of torque. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to apply torque to. 'None' indicates root body. |
| boolean | Accel Change | If true, Torque is taken as a change in angular acceleration instead of a physical torque (i.e. mass will have no effect). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
