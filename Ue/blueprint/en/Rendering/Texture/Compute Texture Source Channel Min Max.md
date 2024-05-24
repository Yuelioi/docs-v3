---
display_name: Compute Texture Source Channel Min Max
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Texture](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Texture)

Scan the texture source pixels to compute the min & max values of the RGBA channels.
Uses texture source, not available in runtime games.
Causes texture source data to be loaded, is computed by scanning pixels when called.
Will set Min=Max=zero and return false on failure

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
| linearcolor | Out Color Min |  |
| linearcolor | Out Color Max |  |
| boolean | Return Value | Scan the texture source pixels to compute the min & max values of the RGBA channels.Uses texture source, not available in runtime games.Causes texture source data to be loaded, is computed by scanning pixels when called.Will set Min=Max=zero and return false on failure |
