---
title: Validate Material Slots
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent)

Compute the maximum MaterialID on the DynamicMesh, and ensure that Material Slots match.
Pass both arguments as false to just do a check.

Target is Dynamic Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Create if Missing | if true, add extra (empty) Material Slots to match max MaterialID |
| boolean | Delete Extra Slots | if true, extra Material Slots beyond max MaterialID are removed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if at the end of this function, Material Slot Count == Max MaterialID |
