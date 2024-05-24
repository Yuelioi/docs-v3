---
display_name: Read Render Target Raw UVArea
order: 74
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Incredibly inefficient and slow operation! Read an area of values as-is from a render target using a rectangle defined by UV \[0,1\]x\[0,1\] coordinates.

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |
| struct | Area |  |
| boolean | Normalize |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| linearcolor | Return Value | Incredibly inefficient and slow operation! Read an area of values as-is from a render target using a rectangle defined by UV \[0,1\]x\[0,1\] coordinates. |
