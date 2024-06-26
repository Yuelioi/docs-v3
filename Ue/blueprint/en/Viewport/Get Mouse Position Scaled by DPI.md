---
title: Get Mouse Position Scaled by DPI
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Viewport](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Viewport)

Gets the mouse position of the player controller, scaled by the DPI. If you're trying to go from raw mouse screenspace coordinates
to fullscreen widget space, you'll need to transform the mouse into DPI Scaled space. This function performs that scaling.

MousePositionScaledByDPI = MousePosition * (1 / ViewportScale).
//UE_DEPRECATED(4.17, "Use GetMousePositionOnViewport() instead. Optionally and for more options, you can use GetViewportWidgetGeometry and GetPlayerScreenWidgetGeometry are newly introduced to give you the geometry of the viewport and the player screen for widgets to help convert between spaces.")

Target is Widget Layout Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Player |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Location X |  |
| real | Location Y |  |
| boolean | Return Value | Gets the mouse position of the player controller, scaled by the DPI. If you're trying to go from raw mouse screenspace coordinatesto fullscreen widget space, you'll need to transform the mouse into DPI Scaled space. This function performs that scaling.MousePositionScaledByDPI = MousePosition * (1 / ViewportScale).//UE_DEPRECATED(4.17, "Use GetMousePositionOnViewport() instead. Optionally and for more options, you can use GetViewportWidgetGeometry and GetPlayerScreenWidgetGeometry are newly introduced to give you the geometry of the viewport and the player screen for widgets to help convert between spaces.") |
