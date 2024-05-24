---
display_name: Update Resource
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas Render Target 2D](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CanvasRenderTarget2D)

Updates the the canvas render target texture's resource. This is where the render target will create or
find a canvas object to use. It also calls UpdateResourceImmediate() to clear the render target texture
from the deferred rendering list, to stop the texture from being cleared the next frame. From there it
will ask the rendering thread to set up the RHI viewport. The canvas is then set up for rendering and
then the user's update delegate is called. The canvas is then flushed and the RHI resolves the
texture to make it available for rendering.

Target is Canvas Render Target 2D

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
