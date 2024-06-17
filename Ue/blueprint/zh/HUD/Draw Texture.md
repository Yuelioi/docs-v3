---
title: Draw Texture
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Draws a textured quad on the HUD.

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Texture | Texture to draw. |
| real | Screen X | Screen-space X coordinate of upper left corner of the quad. |
| real | Screen Y | Screen-space Y coordinate of upper left corner of the quad. |
| real | Screen W | Screen-space width of the quad (in pixels). |
| real | Screen H | Screen-space height of the quad (in pixels). |
| real | Texture U | Texture-space U coordinate of upper left corner of the quad |
| real | Texture V | Texture-space V coordinate of upper left corner of the quad. |
| real | Texture UWidth | Texture-space width of the quad (in normalized UV distance). |
| real | Texture VHeight | Texture-space height of the quad (in normalized UV distance). |
| linearcolor | Tint Color | Vertex color for the quad. |
| enum | Blend Mode | Controls how to blend this quad with the scene. Translucent by default. |
| real | Scale | Amount to scale the entire texture (horizontally and vertically) |
| boolean | Scale Position | Whether the "Scale" parameter should also scale the position of this draw call. |
| real | Rotation | Amount to rotate this quad |
| vector2d struct | Rot Pivot | Location (as proportion of quad, 0-1) to rotate about |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
