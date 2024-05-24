---
display_name: Get Bone Pose
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Pose)

Retrieves the transform for the provided bone name from a pose

Target is Anim Pose Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Pose | Anim Pose to retrieve the transform from |
| name | Bone Name | Name of the bone to retrieve |
| enum | Space | Space in which the transform should be retrieved |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Transform in requested space for bone if found, otherwise return identity transform |
