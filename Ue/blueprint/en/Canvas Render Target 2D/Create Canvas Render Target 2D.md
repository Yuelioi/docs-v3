---
display_name: Create Canvas Render Target 2D
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas Render Target 2D](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CanvasRenderTarget2D)

Creates a new canvas render target and initializes it to the specified dimensions

Target is Canvas Render Target 2D

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Canvas Render Target 2DClass | Class of the render target. Unless you want to use a special sub-class, you can simply pass UCanvasRenderTarget2D::StaticClass() here. |
| integer | Width | Width of the render target. |
| integer | Height | Height of the render target. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Returns the instanced render target. |
