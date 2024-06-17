---
title: Extend Menu
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Tool Menus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ToolMenus)

Extends a menu without registering the menu or claiming ownership of it. Ok to call even if menu does not exist yet.

Target is Tool Menus

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | Name of the menu to extend |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | ToolMenu Menu object |
