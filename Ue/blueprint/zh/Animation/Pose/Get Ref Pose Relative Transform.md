---
display_name: Get Ref Pose Relative Transform
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Pose)

Retrieves the relative transform for the reference pose between the two provided bone names

Target is Anim Pose Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Pose | Anim Pose to retrieve the transform from |
| name | From Bone Name | Name of the bone to retrieve the transform relative from |
| name | To Bone Name | Name of the bone to retrieve the transform relative to |
| enum | Space | Space in which the transform should be retrieved |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Relative transform in requested space for bone if found, otherwise return identity transform |
