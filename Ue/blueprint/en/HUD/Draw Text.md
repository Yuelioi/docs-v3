---
display_name: Draw Text
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Draws a string on the HUD.

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Text | String to draw |
| linearcolor | Text Color | Color to draw string |
| real | Screen X | Screen-space X coordinate of upper left corner of the string. |
| real | Screen Y | Screen-space Y coordinate of upper left corner of the string. |
| object | Font | Font to draw text. If NULL, default font is chosen. |
| real | Scale | Scale multiplier to control size of the text. |
| boolean | Scale Position | Whether the "Scale" parameter should also scale the position of this draw call. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
