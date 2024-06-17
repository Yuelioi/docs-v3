---
title: Get Metadata Keys And Values For Value
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/Scene)

Get the keys and values for which the associated value contains the string to match for the metadata element associated with the given object.

Target is Datasmith Scene Element Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Object | The Object that is associated with the metadata element of interest. |
| string | String to Match | The string to match in the values. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Keys | Output array of keys for which the associated values contain the string to match. |
| string | Out Values | Output array of values associated to the keys. |
