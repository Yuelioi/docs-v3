---
display_name: Draw Material
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Draws a material-textured quad on the HUD.

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
| real | Material U | Texture-space U coordinate of upper left corner of the quad |
| real | Material V | Texture-space V coordinate of upper left corner of the quad. |
| real | Material UWidth | Texture-space width of the quad (in normalized UV distance). |
| real | Material VHeight | Texture-space height of the quad (in normalized UV distance). |
| real | Scale | Amount to scale the entire texture (horizontally and vertically) |
| boolean | Scale Position | Whether the "Scale" parameter should also scale the position of this draw call. |
| real | Rotation | Amount to rotate this quad |
| vector2d struct | Rot Pivot | Location (as proportion of quad, 0-1) to rotate about |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
