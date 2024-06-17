---
title: Get Property from Leaf
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Concert](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Concert) > [Replication](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Concert/Replication)

Gets the property at Index starting from the leaf most property.
Example: The leaf Index 0 for \["RelativeLocation", "X"\] would return "X".

Target is Concert Replication Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Path | The property path to get the sub-property from. |
| integer | Index | The index in the path counting from the right, leaf property. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | The property name at Index or None if Index is invalid. |
