---
title: Get Control Preferred Rotator
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns a control's preferred rotator (local transform rotation)

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | In Key | The key of the element to retrieve the current value for |
| boolean | Initial | If true we'll return the preferred rotator for the initial - otherwise current transform |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | Returns the current preferred rotator |
