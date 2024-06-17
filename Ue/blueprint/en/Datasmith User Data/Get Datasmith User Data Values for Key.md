---
title: Get Datasmith User Data Values for Key
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith User Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DatasmithUserData)

Get the values of the given key for the Datasmith User Data of the given object.

Target is Datasmith Content Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The Object from which to retrieve the Datasmith User Data. |
| name | Key | The key to find in the Datasmith User Data. |
| boolean | Partial Match Key | If true, check for contains, rather than exact match. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | The string value associated with the given key |
