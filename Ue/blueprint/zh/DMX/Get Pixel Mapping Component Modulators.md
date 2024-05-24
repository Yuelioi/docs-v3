---
display_name: Get Pixel Mapping Component Modulators
order: 52
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [DMX](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX)

Returns the Modulators of the component corresponding to the patch specified.
Note, this node does a lookup on all fixture patches in use, hence may be slow and shouldn't be called on tick.

Target is DMXPixel Mapping Renderer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Fixture Patch Ref |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | DMXModulators |  |
| boolean | Return Value | Returns the Modulators of the component corresponding to the patch specified.Note, this node does a lookup on all fixture patches in use, hence may be slow and shouldn't be called on tick. |
