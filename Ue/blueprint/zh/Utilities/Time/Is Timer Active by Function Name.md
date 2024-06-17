---
title: Is Timer Active by Function Name
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Time)

Returns true if a timer exists and is active for the given delegate, false otherwise.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | Object that implements the delegate function. Defaults to self (this blueprint) |
| string | Function Name | Delegate function name. Can be a K2 function or a Custom Event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the timer exists and is active. |
