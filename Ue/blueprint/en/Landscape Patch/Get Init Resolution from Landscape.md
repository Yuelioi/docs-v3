---
title: Get Init Resolution from Landscape
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape Patch](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LandscapePatch)

Given the landscape resolution, current patch coverage, and a landscape resolution multiplier, gives the
needed resolution of the landscape patch. I.e., figures out the number of pixels in the landcape that
would be in a region of such size, and then uses the resolution multiplier to give a result.

Target is Landscape Texture Patch

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Resolution Multiplier |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Resolution Out |  |
| boolean | Success | true if successful (may fail if landscape is not set, for instance) |
