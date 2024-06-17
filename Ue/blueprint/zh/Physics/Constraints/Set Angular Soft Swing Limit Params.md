---
title: Set Angular Soft Swing Limit Params
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Sets Constraint Angular Soft Swing Limit parameters

Target is Constraint Instance Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Accessor | Constraint accessor to change * |
| boolean | Soft Swing Limit | True is the swing limit is soft |
| real | Swing Limit Stiffness | Stiffness of the soft swing limit. Only used when Soft limit is on ( positive value ) |
| real | Swing Limit Damping | Damping of the soft swing limit. Only used when Soft limit is on ( positive value ) |
| real | Swing Limit Restitution | Controls the amount of bounce when the constraint is violated. A restitution value of 1 will bounce back with the same velocity the limit was hit. A value of 0 will stop dead. |
| real | Swing Limit Contact Distance | Determines how close to the limit we have to get before turning the joint on. Larger value will be more expensive, but will do a better job not violating constraints. A smaller value will be more efficient, but easier to violate. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
