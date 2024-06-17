---
title: Get Slot Tags
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the list of tags associated to the smart object slot represented by the provided handle.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Slot Handle | Handle to the smart object slot. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Container of tags associated to the smart object instance, or empty container if slot was not valid. |
