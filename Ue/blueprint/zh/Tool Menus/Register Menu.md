---
title: Register Menu
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Tool Menus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ToolMenus)

Registers a menu by name

Target is Tool Menus

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name |  |
| name | Parent | Optional name of a menu to layer on top of. |
| enum | Type | Type of menu that will be generated such as: ToolBar, VerticalToolBar, etc.. |
| boolean | Warn if Already Registered | Display warning if already registered |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | ToolMenu Menu object |
