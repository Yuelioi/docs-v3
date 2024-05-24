---
display_name: GetTextureSourceDiskAndMemorySize
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Texture](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Texture)

Gets the memory size of the texture source top mip, in bytes, and the size on disk of the asset, which may be compressed.
Uses texture source, not available in runtime games.
Does not cause texture source to be loaded, queries cached values.
Returns zero for error.

Target is Texture

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| int64 | Out Disk Size |  |
| int64 | Out Memory Size |  |
