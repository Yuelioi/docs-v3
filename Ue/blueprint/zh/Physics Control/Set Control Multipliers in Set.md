---
title: Set Control Multipliers in Set
order: 88
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies existing control data using the multipliers

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Set | The set of controls to modify. Standard sets will include "All", "WorldSpace", "ParentSpace" and things like "WorldSpace-ArmLeft", depending on how controls have been created. |
| struct | Control Multiplier | The new control multiplier |
| boolean | Enable Control | Enables the controls if currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
