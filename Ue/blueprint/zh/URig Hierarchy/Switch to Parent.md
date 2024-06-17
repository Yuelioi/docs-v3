---
title: Switch to Parent
order: 171
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Switches a multi parent element to a single parent.
This sets the new parent's weight to 1.0 and disables
weights for all other potential parents.

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the multi parented element |
| struct | In Parent | The key of the parent to look up the weight for |
| boolean | Initial | If true the initial weights will be used |
| boolean | Affect Children | If set to false children will not move (maintain global). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if changing the weight was successful |
