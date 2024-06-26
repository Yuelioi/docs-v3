---
title: Get Global Transform
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns the global current or initial value for a given key.
If the key is invalid FTransform::Identity will be returned.

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | In Key | The key to retrieve the transform for |
| boolean | Initial | If true the initial transform will be used |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | The global current or initial transform's value. |
