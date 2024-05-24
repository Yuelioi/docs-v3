---
display_name: Get Datasmith User Data Keys and Values for Value
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith User Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DatasmithUserData)

Get the keys and values for which the associated value contains the string to match for the Datasmith User Data of the given object.

Target is Datasmith Content Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The Object from which to retrieve the Datasmith User Data. |
| string | String to Match | The string to match in the values. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Out Keys | Output array of keys for which the associated values contain the string to match. |
| string | Out Values | Output array of values associated to the keys. |
