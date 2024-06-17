---
title: Render Heightmap
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape) > [Runtime](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape/Runtime)

Render the final heightmap in the requested top-down window as one -atlased- texture in the provided render target 2D
Can be called at runtime.

Target is Landscape

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| transform | In World Transform | World transform of the area where the texture should be rendered |
| struct | In Extents | Extents of the area where the texture should be rendered (local to InWorldTransform). If size is zero, then the entire loaded landscape will be exported. |
| object | Out Render Target | Render target in which the texture will be rendered. The size/format of the render target will be respected. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | false in case of failure (e.g. invalid inputs, incompatible render target format...) |
