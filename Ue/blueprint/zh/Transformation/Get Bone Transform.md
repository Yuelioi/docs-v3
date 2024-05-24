---
display_name: Get Bone Transform
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Get world-space bone transform.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | In Bone Name | Name of the the bone to get the transform |
| enum | Transform Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Bone transform in world space if bone is found. Otherwise it will return component's transform in world space. |
