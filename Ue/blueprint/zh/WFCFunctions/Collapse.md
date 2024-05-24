---
display_name: Collapse
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [WFCFunctions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WFCFunctions)

Solve a grid using a WFC model. If successful, spawn an actor.

Target is Wave Function Collapse Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Try Count | Amount of times to attempt a successful solve |
| integer | Random Seed | Seed for deterministic results. When this value is 0 the seed will be generated. Seed value will be logged during the solve. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
