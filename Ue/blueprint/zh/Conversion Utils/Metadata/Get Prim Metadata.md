---
title: Get Prim Metadata
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Conversion Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ConversionUtils) > [Metadata](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ConversionUtils/Metadata)

Extracts metadata from the prim at PrimPath using the provided filters and returns it

Target is Usd Conversion Blueprint Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Prim Path |  |
| string | Blocked Prefix Filter |  |
| boolean | Invert Filter |  |
| boolean | Collect from Entire Subtrees |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Extracts metadata from the prim at PrimPath using the provided filters and returns it |
