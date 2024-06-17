---
title: Make Input Action Value Of Type
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Builds an ActionValue from X, Y, Z. Inherits type from an existing ActionValue. Ignores axis values unused by the provided value type.
Note: Intended for use in Input Modifier Modify Raw overloads to modify an existing Input Action Value.

Target is Enhanced Input Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| real | X |  |
| real | Y |  |
| real | Z |  |
| enum | Value Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Builds an ActionValue from X, Y, Z. Inherits type from an existing ActionValue. Ignores axis values unused by the provided value type.@note Intended for use in Input Modifier Modify Raw overloads to modify an existing Input Action Value. |
