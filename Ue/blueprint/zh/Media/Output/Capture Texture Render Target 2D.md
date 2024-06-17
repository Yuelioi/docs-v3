---
title: Capture Texture Render Target 2D
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Output](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/Output)

Stop the actual capture if there is one.
Then capture every frame for a TextureRenderTarget2D.
The TextureRenderTarget2D needs to be of the same size and have the same pixel format as requested by the media output.

Target is Media Capture

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Target |  |
| struct | Capture Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the capture was successfully started |
