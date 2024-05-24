---
display_name: Set Timer for Next Tick by Function Name
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Time)

Set a timer to execute a delegate on the next tick.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | Object that implements the delegate function. Defaults to self (this blueprint) |
| string | Function Name | Delegate function name. Can be a K2 function or a Custom Event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The timer handle to pass to other timer functions to manipulate this timer. |
