---
display_name: Add Timed Display
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Viewport Stats Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ViewportStatsSubsystem)

Add a message to be displayed on the viewport of this world

Target is Viewport Stats Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| text | Text | The text to be displayed |
| linearcolor | Color | Color of the text to be displayed |
| real | Duration | How long the text will be on screen, if 0 then it will stay indefinitely |
| vector2d struct | Display Offset | A position offset that the message should use when displayed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
