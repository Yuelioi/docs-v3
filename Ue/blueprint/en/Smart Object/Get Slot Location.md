---
display_name: Get Slot Location
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the position (in world space) of the slot associated to the given claim handle.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Claim Handle | Handle to a claimed slot returned by any of the Claim methods. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Slot Location | Position (in world space) of the slot associated to ClaimHandle. |
| boolean | Return Value | Whether the location was found and assigned to 'OutSlotLocation' |
