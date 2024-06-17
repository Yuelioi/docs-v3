---
title: Set Position in Viewport
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Viewport](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Viewport)

Sets the widgets position in the viewport.

Target is User Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector2d struct | Position | The 2D position to set the widget to in the viewport. |
| boolean | Remove DPIScale | If you've already calculated inverse DPI, set this to false. Otherwise inverse DPI is applied to the position so that when the location is scaled by DPI, it ends up in the expected position. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
