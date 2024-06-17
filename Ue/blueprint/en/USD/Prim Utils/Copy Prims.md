---
title: Copy Prims
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Prim Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/PrimUtils)

Copies flattened versions of the input prims onto the clipboard stage.
These copied prims can then be pasted with PastePrims.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Stage Root Layer | Path to the root layer of the stage from which we should fetch the Prims |
| string | Prim Paths | Prims to copy |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if we managed to copy |
