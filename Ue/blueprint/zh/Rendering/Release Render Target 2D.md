---
display_name: Release Render Target 2D
order: 79
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Manually releases GPU resources of a render target. This is useful for blueprint creating a lot of render target that would
normally be released too late by the garbage collector that can be problematic on platforms that have tight GPU memory constrains.

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Texture Render Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
