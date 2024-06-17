---
title: Snap to Landscape
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Initialization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Initialization)

Adjusts patch rotation to be aligned to a 90 degree increment relative to the landscape,
adjusts UnscaledPatchCoverage such that it becomes a multiple of landscape quad size, and
adjusts patch location so that the boundaries of the covered area lie on the nearest
landscape vertices.
Note that this doesn't adjust the resolution of the texture that the patch uses, so landscape
vertices within the inside of the patch may still not always align with texture patch pixel
centers (if the resolutions aren't multiples of each other).

Target is Landscape Texture Patch

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
