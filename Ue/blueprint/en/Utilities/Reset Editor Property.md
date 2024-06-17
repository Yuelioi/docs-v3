---
title: Reset Editor Property
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Attempts to reset the value of a named property on the given object so that it matches the value of the archetype.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The object you want to reset a property value on. |
| name | Property Name | The name of the object property to reset the value of. |
| enum | Change Notify Mode | When to emit property change notifications. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether the property value was found and correctly reset. |
