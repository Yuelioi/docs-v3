---
title: Draw Material Simple
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Draws a material-textured quad on the HUD. Assumes UVs such that the entire material is shown.

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Material | Material to use |
| real | Screen X | Screen-space X coordinate of upper left corner of the quad. |
| real | Screen Y | Screen-space Y coordinate of upper left corner of the quad. |
| real | Screen W | Screen-space width of the quad (in pixels). |
| real | Screen H | Screen-space height of the quad (in pixels). |
| real | Scale | Amount to scale the entire texture (horizontally and vertically) |
| boolean | Scale Position | Whether the "Scale" parameter should also scale the position of this draw call. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
