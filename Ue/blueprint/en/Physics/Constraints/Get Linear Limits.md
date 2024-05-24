---
display_name: Get Linear Limits
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Gets Constraint Linear Motion Ranges

Target is Constraint Instance Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Accessor | Constraint accessor to query |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | XMotion | Type of motion along the X axis |
| enum | YMotion | Type of motion along the Y axis |
| enum | ZMotion | Type of motion along the Z axis |
| real | Limit | linear limit applied to all axis |
