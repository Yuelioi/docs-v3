---
display_name: Get Angular Velocity Drive SLERP
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Gets whether the angular velocity slerp drive is enabled or not. Only relevant if the AngularDriveMode is set to SLERP

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
| boolean | Out Enable SLERP | Indicates whether the SLERP drive is enabled. Only relevant if the AngularDriveMode is set to SLERP |
