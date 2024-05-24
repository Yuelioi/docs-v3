---
display_name: Get Goal Settings for Solver
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [IKRig](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/IKRig)

Get the UObject for the settings associated with the given Goal in the given Solver.
Solvers can define their own per-Goal settings depending on their needs. These are termed "Effectors".

Target is IKRig Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Goal Name |  |
| integer | Solver Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Get the UObject for the settings associated with the given Goal in the given Solver.Solvers can define their own per-Goal settings depending on their needs. These are termed "Effectors". |
