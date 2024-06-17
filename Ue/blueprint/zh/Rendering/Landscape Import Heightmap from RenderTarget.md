---
title: Landscape Import Heightmap from RenderTarget
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Overwrites a landscape heightmap with render target data

Target is Landscape Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Render Target | Valid render target with a format of RTF_RGBA16f, RTF_RGBA32f or RTF_RGBA8 |
| boolean | In Import Height from RGChannel | Only relevant when using format RTF_RGBA16f or RTF_RGBA32f, and will tell us if we should import the height data from the R channel only of the Render target or from R & G. Note that using RTF_RGBA16f with InImportHeightFromRGChannel == false, could have precision loss Only works in the editor |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
