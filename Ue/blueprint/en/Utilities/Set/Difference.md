---
title: Difference
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Set)

Assigns Result to the relative difference of two sets, A and B. That is, Result will
contain all elements that are in Set A but are not found in Set B. Note that the
difference between two sets is not commutative. The Set whose elements you wish to
preserve should be the first (top) parameter. Also called the relative complement.

Target is Blueprint Set Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| wildcard | A | Starting set |
| wildcard | B | Set of elements to remove from set A |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| wildcard | Result | Set containing all elements in A that are not found in B |
