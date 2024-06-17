---
title: Create Drag & Drop Operation
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface)

Creates a new drag drop operation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Class | Drag Drop Operation Class Reference ClassThe object class you want to construct |
| string | Tag | A simple string tag you can optionally use to provide extra metadata about the operation. |
| object | Payload | The payload of the drag operation. This can be any UObject that you want to pass along as dragged data. If youwere building an inventory screen this would be the UObject representing the item being moved to another slot. |
| object | Default Drag Visual | The Drag Visual is the widget to display when dragging the item. Normally people create a new widget to represent thetemporary drag. |
| enum | Pivot | Controls where the drag widget visual will appear when dragged relative to the pointer performingthe drag operation. |
| vector2d struct | Offset | A percentage offset (-1..+1) from the Pivot location, the percentage is of the desired size of the dragged visual. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Drag Drop Operation Object Reference Return ValueThe constructed object |
