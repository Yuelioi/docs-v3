---
title: Set Parent Weight Array
order: 155
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets the all of the weights of the parents of a multi parent element

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the multi parented element |
| struct | In Weights | The new weights to set for the parents |
| boolean | Initial | If true the initial weights will be used |
| boolean | Affect Children | If set to false children will not move (maintain global). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if changing the weight was successful |
