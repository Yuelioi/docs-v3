---
title: Add Type to Packing
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Instance Packing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/InstancePacking)

Interprets Metadata TypeId and increments OutPackedCustomData.NumCustomDataFloats appropriately. Returns false if the type could not be interpreted.

Target is PCGInstance Data Packer Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Type Id |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Packed Custom Data |  |
| boolean | Return Value | Interprets Metadata TypeId and increments OutPackedCustomData.NumCustomDataFloats appropriately. Returns false if the type could not be interpreted. |
