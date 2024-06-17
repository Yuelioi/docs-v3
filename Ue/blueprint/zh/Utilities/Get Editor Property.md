---
title: Get Editor Property
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Attempts to retrieve the value of a named property from the given object.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The object you want to retrieve a property value from. |
| name | Property Name | The name of the object property to retrieve the value from. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| wildcard | Property Value | The retrieved property value, if found. |
| boolean | Success? | Whether the property value was found and correctly retrieved. |
