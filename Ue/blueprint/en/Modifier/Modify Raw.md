---
title: Modify Raw
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Modifier](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Modifier)

ModifyRaw
Will be called by each modifier in the modifier chain

Target is Input Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Player Input |  |
| struct | Current Value | The modified value returned by the previous modifier in the chain, or the base raw value if this is the first modifier in the chain. |
| real | Delta Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value |  |
