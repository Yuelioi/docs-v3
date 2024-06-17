---
title: Connect Material Expressions
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Material Editing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MaterialEditing)

Create connection between two material expressions

Target is Material Editing Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Expression | Expression to make connection from |
| string | From Output Name | Name of output of FromExpression to make connection from. Leave empty to use first output. |
| object | To Expression | Expression to make connection to |
| string | To Input Name | Name of input of ToExpression to make connection to. Leave empty to use first input. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
