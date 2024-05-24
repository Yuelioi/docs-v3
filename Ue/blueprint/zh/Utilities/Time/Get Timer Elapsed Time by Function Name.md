---
display_name: Get Timer Elapsed Time by Function Name
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Time)

Returns elapsed time for the given delegate (time since current countdown iteration began).

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | Object that implements the delegate function. Defaults to self (this blueprint) |
| string | Function Name | Delegate function name. Can be a K2 function or a Custom Event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | How long has elapsed since the current iteration of the timer began. |
