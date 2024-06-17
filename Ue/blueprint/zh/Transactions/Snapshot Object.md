---
title: Snapshot Object
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transactions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transactions)

Notify the current transaction (if any) that this object is about to be modified and should be snapshot for intermediate update.
Note: Internally this calls SnapshotTransactionBuffer on the given object.
Note: Only available in the editor.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The object that is about to be modified. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
