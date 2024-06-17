---
title: Apply Radial Force
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

ApplyRadialForce
This function will dispatch a command to the physics thread to apply
a linear force that points away from a position.

Target is Field System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Field | Is this force enabled for evaluation. |
| vector | Center Position | The origin point of the force |
| real | Field Magnitude | The size of the linear force. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
