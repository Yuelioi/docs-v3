---
title: Set Physics Angular Velocity in Degrees
order: 50
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Set the angular velocity of a single body.
This should be used cautiously - it may be better to use AddTorque or AddImpulse.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | New Ang Vel | New angular velocity to apply to body, in degrees per second. |
| boolean | Add to Current | If true, NewAngVel is added to the existing angular velocity of the body. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to modify angular velocity of. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
