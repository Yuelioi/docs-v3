---
display_name: Get Timer Remaining Time by Function Name
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Time)

Returns time until the timer will next execute its delegate.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | Object that implements the delegate function. Defaults to self (this blueprint) |
| string | Function Name | Delegate function name. Can be a K2 function or a Custom Event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | How long is remaining in the current iteration of the timer. |
