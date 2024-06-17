---
title: Set Linear Drive Params
order: 47
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Sets the drive params for the linear drive.

Target is Constraint Instance Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Accessor | Constraint accessor to change |
| real | Position Strength | Positional strength for the drive (stiffness) |
| real | Velocity Strength | Velocity strength of the drive (damping) |
| real | In Force Limit | Max force applied by the drive |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
