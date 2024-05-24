---
display_name: Get Text Size
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Returns the width and height of a string.

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| string | Text | String to draw |
| object | Font | Font to draw text. If NULL, default font is chosen. |
| real | Scale | Scale multiplier to control size of the text. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Width | Returns the width in pixels of the string. |
| real | Out Height | Returns the height in pixels of the string. |
