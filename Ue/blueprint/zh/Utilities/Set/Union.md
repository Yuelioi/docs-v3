---
title: Union
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Set)

Assigns Result to the union of two sets, A and B. That is, Result will contain
all elements that are in Set A and in addition all elements in Set B. Note that
a Set is a collection of unique elements, so duplicates will be eliminated.

Target is Blueprint Set Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| wildcard | A | One set to union |
| wildcard | B | Another set to union |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| wildcard | Result | Set to store results in |
