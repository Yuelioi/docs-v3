---
display_name: Begin Draw Canvas to Render Target
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Returns a Canvas object that can be used to draw to the specified render target.
Canvas has functions like DrawMaterial with size parameters that can be used to draw to a specific area of a render target.
Be sure to call EndDrawCanvasToRenderTarget to complete the rendering!

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Canvas |  |
| vector2d struct | Size |  |
| struct | Context |  |
