---
title: Get Parent Weight
order: 65
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns the weight of a parent below a multi parent element

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | In Child | The key of the multi parented element |
| struct | In Parent | The key of the parent to look up the weight for |
| boolean | Initial | If true the initial weights will be used |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Returns the weight of a parent below a multi parent element, or FLT_MAX if the parent is invalid |
