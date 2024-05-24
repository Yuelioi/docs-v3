---
display_name: Add Force to All Bodies Below
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Add a force to all rigid bodies below.
This is like a 'thruster'. Good for adding a burst over some (non zero) time. Should be called every frame for the duration of the force.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Force | Force vector to apply. Magnitude indicates strength of force. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to apply force to. 'None' indicates root body. |
| boolean | Accel Change | If true, Force is taken as a change in acceleration instead of a physical force (i.e. mass will have no effect). |
| boolean | Include Self | If false, Force is only applied to bodies below but not given bone name. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
