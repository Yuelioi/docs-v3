---
display_name: Add Force
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Add a force to a single rigid body.
This is like a 'thruster'. Good for adding a burst over some (non zero) time. Should be called every frame for the duration of the force.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Force | Force vector to apply. Magnitude indicates strength of force. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to apply force to. 'None' indicates root body. |
| boolean | Accel Change | If true, Force is taken as a change in acceleration instead of a physical force (i.e. mass will have no effect). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
