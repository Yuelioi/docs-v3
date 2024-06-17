---
title: Read Render Target
order: 77
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Incredibly inefficient and slow operation! Reads entire render target as sRGB color and returns a linear array of sRGB colors.
LDR render targets are assumed to be in sRGB space. HDR ones are assumed to be in linear space.
Result whether the operation succeeded. If successful, OutSamples will an entry per pixel, where each is 8-bit per channel \[0,255\] BGRA in sRGB space.

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |
| boolean | Normalize |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Samples |  |
| boolean | Return Value | Incredibly inefficient and slow operation! Reads entire render target as sRGB color and returns a linear array of sRGB colors.LDR render targets are assumed to be in sRGB space. HDR ones are assumed to be in linear space.Result whether the operation succeeded. If successful, OutSamples will an entry per pixel, where each is 8-bit per channel \[0,255\] BGRA in sRGB space. |
