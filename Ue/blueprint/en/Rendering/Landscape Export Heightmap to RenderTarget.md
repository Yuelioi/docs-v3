---
title: Landscape Export Heightmap to RenderTarget
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Output a landscape heightmap to a render target

Target is Landscape Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Render Target | Valid render target with a format of RTF_RGBA16f, RTF_RGBA32f or RTF_RGBA8 |
| boolean | In Export Height Into RGChannel | Tell us if we should export the height that is internally stored as R & G (for 16 bits) to a single R channel of the render target (the format need to be RTF_RGBA16f or RTF_RGBA32f) Note that using RTF_RGBA16f with InExportHeightIntoRGChannel == false, could have precision loss. |
| boolean | In Export Landscape Proxies | Option to also export components of all proxies of Landscape actor (if LandscapeProxy is the Landscape Actor) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
