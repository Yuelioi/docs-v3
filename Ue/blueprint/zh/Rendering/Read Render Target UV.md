---
display_name: Read Render Target UV
order: 76
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Incredibly inefficient and slow operation! Read a value as sRGB color from a render target using UV \[0,1\]x\[0,1\] coordinates.
LDR render targets are assumed to be in sRGB space. HDR ones are assumed to be in linear space.
Result is 8-bit per channel \[0,255\] BGRA in sRGB space.

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |
| real | U |  |
| real | V |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Incredibly inefficient and slow operation! Read a value as sRGB color from a render target using UV \[0,1\]x\[0,1\] coordinates.LDR render targets are assumed to be in sRGB space. HDR ones are assumed to be in linear space.Result is 8-bit per channel \[0,255\] BGRA in sRGB space. |
