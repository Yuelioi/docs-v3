---
title: Get All Widgets Of Class
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget)

Find all widgets of a certain class.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Widget Class | The widget class to filter by. |
| boolean | Top Level Only | Only the widgets that are direct children of the viewport will be returned. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Found Widgets | The widgets that were found matching the filter. |
