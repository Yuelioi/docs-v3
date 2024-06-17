---
title: Request Rebuild Control Mappings Using Context
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Flag all enhanced input subsystems making use of the mapping context for reapplication of all control mappings at the end of this frame.

Target is Enhanced Input Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Context | Mappings will be rebuilt for all subsystems utilizing this context. |
| boolean | Force Immediately | The mapping changes will be applied synchronously, rather than at the end of the frame, making them available to the input system on the same frame. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
