---
title: Connect Material Property
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Material Editing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MaterialEditing)

Connect a material expression output to one of the material property inputs (e.g. diffuse color, opacity etc)

Target is Material Editing Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Expression | Expression to make connection from |
| string | From Output Name | Name of output of FromExpression to make connection from |
| enum | Property | Property input on material to make connection to |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
