---
display_name: End Transaction
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transactions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transactions)

Attempt to end the current undo transaction. Only successful if the transaction's action counter is 1.
Note: Only available in the editor.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The number of active actions when EndTransaction was called (a value of 1 indicates that the transaction was successfully closed), or -1 on failure. |
