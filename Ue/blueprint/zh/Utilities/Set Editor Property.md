---
title: Set Editor Property
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Attempts to set the value of a named property on the given object.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The object you want to set a property value on. |
| name | Property Name | The name of the object property to set the value of. |
| wildcard | Property Value | The property value to set. |
| enum | Change Notify Mode | When to emit property change notifications. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success? | Whether the property value was found and correctly set. |
