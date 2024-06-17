---
title: Apply Color Space Transform to Texture Compressed
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Open Color IO](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OpenColorIO)

Apply a color space transform with a target compression setting to a texture asset.

Target is Open Color IOEditor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Conversion Settings | Color transformation settings. |
| enum | Target Compression | Target texture compression setting. |
| object | In Out Texture | Texture object to transform. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true upon success. |
