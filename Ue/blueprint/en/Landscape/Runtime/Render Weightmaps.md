---
display_name: Render Weightmaps
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape) > [Runtime](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape/Runtime)

Render the final weightmaps for the requested layers, in the requested top-down window, as one -atlased- texture in the provided render target (2D or 2DArray)
Can be called at runtime.

Target is Landscape

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| transform | In World Transform | World transform of the area where the texture should be rendered |
| struct | In Extents | Extents of the area where the texture should be rendered (local to InWorldTransform). If size is zero, then the entire loaded landscape will be exported. |
| name | In Weightmap Layer Names | List of weightmap layers that are being requested to render |
| object | Out Render Target | Render target in which the texture will be rendered. The size/format of the render target will be respected. - If a UTextureRenderTarget2D is passed, the requested layers will be packed in the RGBA channels in order (up to the number of channels available with the render target's format). - If a UTextureRenderTarget2DArray is passed, the requested layers will be packed in the RGBA channels of each slice (up to the number of channels * slices available with the render target's format and number of slices). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | false in case of failure (e.g. invalid inputs, incompatible render target format...) |
