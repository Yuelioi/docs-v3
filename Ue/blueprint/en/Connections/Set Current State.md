---
display_name: Set Current State
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Connections](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Connections)

Switches to given state - if the state transition is valid, UpdateConnectionTargets will be called.
If CurrentState == NewState, then this call will be ignored (unless bForceUpdate == true).

Target is VCam State Switcher Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | New State | The new state to switch to |
| boolean | Force Update | Call UpdateConnectionTargets even if the CurrentState == NewState |
| boolean | Reinitialize Connections | Parameter to pass to UpdateConnectionTargets. If true, ReinitializeConnections will be called. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
