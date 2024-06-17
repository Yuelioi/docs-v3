---
title: Add Mapping Context
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Add a control mapping context.

Target is Enhanced Input Subsystem Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| object | Mapping Context | A set of key to action mappings to apply to this player |
| integer | Priority | Higher priority mappings will be applied first and, if they consume input, will block lower priority mappings. |
| struct | Options | Options to consider when adding this mapping context. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
