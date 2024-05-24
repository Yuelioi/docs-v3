---
display_name: Set Physics Linear Velocity
order: 53
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Set the linear velocity of a single body.
This should be used cautiously - it may be better to use AddForce or AddImpulse.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | New Vel | New linear velocity to apply to physics. |
| boolean | Add to Current | If true, NewVel is added to the existing velocity of the body. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to modify velocity of. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
