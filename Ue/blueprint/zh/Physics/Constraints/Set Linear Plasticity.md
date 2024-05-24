---
display_name: Set Linear Plasticity
order: 49
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Sets Constraint Linear Plasticity properties

Target is Constraint Instance Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Accessor | Constraint accessor to change |
| boolean | Linear Plasticity | Whether it is possible to reset the target position from the linear displacement |
| real | Linear Plasticity Threshold | Delta from target needed to reset the target joint |
| enum | Plasticity Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
