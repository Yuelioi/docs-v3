---
display_name: Is Running
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Calibration](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Calibration)

Returns true if the solver is currently running, and false if it has been cancelled. The solver should call this in critical loops in order to respond to cancellation requests.

Target is Lens Distortion Solver

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if the solver is currently running, and false if it has been cancelled. The solver should call this in critical loops in order to respond to cancellation requests. |
