---
display_name: Get Angular Drive Params
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Gets the drive params for the angular drive.

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
| real | Out Position Strength | Positional strength for the drive (stiffness) |
| real | Out Velocity Strength | Velocity strength of the drive (damping) |
| real | Out Force Limit | Max force applied by the drive |
