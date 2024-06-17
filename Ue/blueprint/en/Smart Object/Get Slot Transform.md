---
title: Get Slot Transform
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the transform (in world space) of the slot associated to the given claim handle.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Claim Handle | Handle to a claimed slot returned by any of the Claim methods. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Out Slot Transform | Transform (in world space) of the slot associated to ClaimHandle. |
| boolean | Return Value | Whether the transform was found and assigned to 'OutSlotTransform' |
