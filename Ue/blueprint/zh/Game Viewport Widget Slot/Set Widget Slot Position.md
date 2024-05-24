---
display_name: Set Widget Slot Position
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game Viewport Widget Slot](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameViewportWidgetSlot)

Helper function to set the position in the viewport for the Slot.

Target is Game Viewport Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Slot |  |
| object | Widget |  |
| vector2d struct | Position | The 2D position to set the widget to in the viewport. |
| boolean | Remove DPIScale | If you've already calculated inverse DPI, set this to false. Otherwise inverse DPI is applied to the position so that when the location is scaled by DPI, it ends up in the expected position. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |
