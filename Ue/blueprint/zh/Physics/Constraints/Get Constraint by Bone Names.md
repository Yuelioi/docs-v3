---
display_name: Get Constraint by Bone Names
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Gets a constraint by its joint name

Target is Physics Asset

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone 1Name | name of the first bone in the joint |
| name | Bone 2Name | name of the second bone in the joint |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | ConstraintInstance accessor to the constraint data |
