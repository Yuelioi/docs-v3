---
display_name: Get Current Joint Angles
order: 72
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Gets the current Angular state for a named bone constraint

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Bone Name | Name of bone to get constraint ranges for |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Swing 1Angle | current angular state of the constraint |
| real | Twist Angle | current angular state of the constraint |
| real | Swing 2Angle | current angular state of the constraint |
