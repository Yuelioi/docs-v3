---
display_name: Apply External Strain
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

ApplyExternalStran
This function will dispatch a command to the physics thread to apply
a strain field on a clustered set of geometry. This is used to trigger a
breaking event within the solver.

Target is Field System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Field | Is this force enabled for evaluation. |
| vector | Center Position | The origin point of the force |
| real | Falloff Radius | Radial influence from the position, positions further away are weaker. |
| real | Field Magnitude | The size of the linear force. |
| integer | Cluster Levels | Levels of evaluation into the cluster hierarchy. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
