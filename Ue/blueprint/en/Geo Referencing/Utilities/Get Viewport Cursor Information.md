---
display_name: Get Viewport Cursor Information
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geo Referencing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing/Utilities)

Retrieve information about the viewport under the mouse cursor.

Target is Geo Referencing Editor BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Focused | If the Level editor not are in focus it will return false. |
| vector2d struct | Screen Location | Viewport-Space position of cursor. |
| vector | World Location | Location of viewport origin (camera) in world space. |
| vector | World Direction | Direction of viewport (camera) in world space. |
