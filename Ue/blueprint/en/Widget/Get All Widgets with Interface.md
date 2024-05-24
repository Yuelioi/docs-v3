---
display_name: Get All Widgets with Interface
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget)

Find all widgets in the world with the specified interface.
This is a slow operation, use with caution e.g. do not use every frame.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Interface | The interface to find. Must be specified or result array will be empty. |
| boolean | Top Level Only | Only the widgets that are direct children of the viewport will be returned. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Found Widgets | Output array of widgets that implement the specified interface. |
