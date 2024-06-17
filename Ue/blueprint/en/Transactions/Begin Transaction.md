---
title: Begin Transaction
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transactions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transactions)

Begin a new undo transaction. An undo transaction is defined as all actions which take place when the user selects "undo" a single time.
Note: If there is already an active transaction in progress, then this increments that transaction's action counter instead of beginning a new transaction.
Note: You must call TransactObject before modifying each object that should be included in this undo transaction.
Note: Only available in the editor.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Context | The context for the undo session. Typically the tool/editor that caused the undo operation. |
| text | Description | The description for the undo session. This is the text that will appear in the "Edit" menu next to the Undo item. |
| object | Primary Object | The primary object that the undo session operators on (can be null, and mostly is). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The number of active actions when BeginTransaction was called (values greater than 0 indicate that there was already an existing undo transaction in progress), or -1 on failure. |
