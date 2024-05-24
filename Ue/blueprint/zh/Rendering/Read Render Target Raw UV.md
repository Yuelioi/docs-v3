---
display_name: Read Render Target Raw UV
order: 73
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Incredibly inefficient and slow operation! Read a value as-is from a render target using UV \[0,1\]x\[0,1\] coordinates.

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |
| real | U |  |
| real | V |  |
| boolean | Normalize |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| linearcolor | Return Value | Incredibly inefficient and slow operation! Read a value as-is from a render target using UV \[0,1\]x\[0,1\] coordinates. |
