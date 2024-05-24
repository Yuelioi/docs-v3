---
display_name: Cancel Transaction
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transactions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transactions)

Cancel the current transaction, and no longer capture actions to be placed in the undo buffer.
Note: Only available in the editor.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Index | The action counter to cancel transactions from (as returned by a call to BeginTransaction). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
