---
display_name: Draw Texture Simple
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Draws a textured quad on the HUD. Assumes 1:1 texel density.

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Texture | Texture to draw. |
| real | Screen X | Screen-space X coordinate of upper left corner of the quad. |
| real | Screen Y | Screen-space Y coordinate of upper left corner of the quad. |
| real | Scale | Scale multiplier to control size of the text. |
| boolean | Scale Position | Whether the "Scale" parameter should also scale the position of this draw call. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
