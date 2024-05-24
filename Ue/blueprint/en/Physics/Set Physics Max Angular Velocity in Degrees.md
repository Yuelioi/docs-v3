---
display_name: Set Physics Max Angular Velocity in Degrees
order: 54
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Set the maximum angular velocity of a single body.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | New Max Ang Vel | New maximum angular velocity to apply to body, in degrees per second. |
| boolean | Add to Current | If true, NewMaxAngVel is added to the existing maximum angular velocity of the body. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to modify maximum angular velocity of. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
