---
title: Create Composure Element
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Composure](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Composure) > [Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Composure/Manager)

Create a new Composure in the level without any parenting relationship.

Target is Composure Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Element Name | The name for the newly created composure element |
| class | Class Type | The type for the new composure element |
| object | Level Context | The level context of current level. Default value is nullptr. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | CompositingElement The created composure element. |
