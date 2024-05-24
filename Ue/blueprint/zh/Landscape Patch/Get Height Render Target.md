---
display_name: Get Height Render Target
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape Patch](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LandscapePatch)

Gets the internal height render target, if source mode is set to Texture Backed Render Target.

Things that should be set up if using the internal render target:

- SetHeightSourceMode should have been called with TextureBackedRenderTarget.
- An appropriate texture size should have been set with SetResolution. If the patch extent has already
  been set, you can base your resolution on the extent and the resolution of the landscape by using
  GetInitResolutionFromLandscape().
- SetHeightRenderTargetFormat should have been called with a desired format. In particular, if using
  an alpha channel, the format should have an alpha channel (and SetUseAlphaChannelForHeight should have
  been called with "true").

In addition, you may need to call SetHeightEncodingMode, SetHeightEncodingSettings, and SetZeroHeightMeaning
based on how you want the data you write to be interpreted. This part is not specific to using an internal render
target, since you are likely to need to do that with a TextureAsset source mode as well.

Target is Landscape Texture Patch

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Mark Dirty | If true, marks the containing package as dirty, since the render target is presumably being written to. Can be set to false if the render target is not being written to. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
