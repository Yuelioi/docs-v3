---
title: Apply Uniform Force
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

ApplyUniformForce
This function will dispatch a command to the physics thread to apply
a uniform linear force on each particle within the simulation.

Target is Field System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Field | Is this force enabled for evaluation. |
| vector | Uniform Direction | The direction of the linear force |
| real | Field Magnitude | The size of the linear force. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
