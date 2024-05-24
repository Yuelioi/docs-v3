---
display_name: Get whether or not to lock the desired age delta time to the seek delta.
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Gets whether or not the delta time used to tick the system instance when using desired age is locked to the seek delta. When true, the system instance
will only be ticked when the desired age has changed by more than the seek delta. When false the system instance will be ticked by the change in desired
age when not seeking.

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Gets whether or not the delta time used to tick the system instance when using desired age is locked to the seek delta. When true, the system instancewill only be ticked when the desired age has changed by more than the seek delta. When false the system instance will be ticked by the change in desiredage when not seeking. |
