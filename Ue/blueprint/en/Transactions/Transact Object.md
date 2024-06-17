---
title: Transact Object
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transactions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transactions)

Notify the current transaction (if any) that this object is about to be modified and should be placed into the undo buffer.
Note: Internally this calls Modify on the given object, so will also mark the owner package dirty.
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
