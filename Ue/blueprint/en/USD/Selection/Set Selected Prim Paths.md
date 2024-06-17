---
title: Set Selected Prim Paths
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/Selection)

Sets the USD Stage Editor prim selection to the prims with paths contained in NewSelection.
Provide an empty array to clear the selection.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | New Selection | The list of prim paths to select (e.g. \["/ParentPrim/Mesh", "/Root"\]) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
