---
display_name: Does Timer Exist by Function Name
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Time)

Returns true is a timer for the given delegate exists, false otherwise.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | Object that implements the delegate function. Defaults to self (this blueprint) |
| string | Function Name | Delegate function name. Can be a K2 function or a Custom Event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the timer exists. |
