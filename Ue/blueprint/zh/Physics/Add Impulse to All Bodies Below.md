---
display_name: Add Impulse to All Bodies Below
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Add impulse to all single rigid bodies below. Good for one time instant burst.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Impulse | Magnitude and direction of impulse to apply. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to apply impulse to. 'None' indicates root body. |
| boolean | Vel Change | If true, the Strength is taken as a change in velocity instead of an impulse (ie. mass will have no effect). |
| boolean | Include Self | If false, Force is only applied to bodies below but not given bone name. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
