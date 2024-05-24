---
display_name: Read Render Target Raw Pixel Area
order: 71
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Incredibly inefficient and slow operation! Read an area of values as-is from a render target using a rectangle defined by integer pixel coordinates.

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |
| integer | Min X |  |
| integer | Min Y |  |
| integer | Max X |  |
| integer | Max Y |  |
| boolean | Normalize |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| linearcolor | Return Value | Incredibly inefficient and slow operation! Read an area of values as-is from a render target using a rectangle defined by integer pixel coordinates. |
