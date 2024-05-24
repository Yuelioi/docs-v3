---
display_name: Add or Update Warp Target from Component
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Warping](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionWarping)

Create and adds or update a target associated with a specified name

Target is Motion Warping Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Warp Target Name | Warp target identifier |
| object | Component | Scene Component used to get the target transform |
| name | Bone Name | Optional bone or socket in the component used to get the target transform. |
| boolean | Follow Component | Whether the target transform should update while the warping is active. Useful for tracking moving targets. Note that this will be one frame off if our owner ticks before the target actor. Add tick pre-requisites to avoid this. |
| vector | Location Offset | Optional translation offset to apply to the transform we get from the component |
| rotator | Rotation Offset | Optional rotation offset to apply to the transform we get from the component |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
