---
display_name: Get Angular Limits
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Gets Constraint Angular Motion Ranges

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
| enum | Swing 1Motion Type | Type of swing motion ( first axis ) |
| real | Swing 1Limit Angle | Size of limit in degrees in \[0, 180\] range |
| enum | Swing 2Motion Type | Type of swing motion ( second axis ) |
| real | Swing 2Limit Angle | Size of limit in degrees in \[0, 180\] range |
| enum | Twist Motion Type | Type of twist motion |
| real | Twist Limit Angle | Size of limit in degrees in \[0, 180\] range |
