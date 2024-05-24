---
display_name: Falloff Uniform Force
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

FalloffUniformForce
This function will dispatch a command to the physics thread to apply
a linear force in a uniform direction. The force vector is weaker as
it moves away from the center.

Target is Field System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Field | Is this force enabled for evaluation. |
| vector | Center Position | The origin point of the force |
| vector | Uniform Direction | The direction of the linear force |
| real | Falloff Radius | Radial influence from the position, positions further away are weaker. |
| real | Field Magnitude | The size of the linear force. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
