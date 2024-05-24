---
display_name: Get Editor Asset Widget
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Appearance](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Appearance)

Gets the widget used for displaying in editor. Returns nullptr in non-editor builds.
This type must be cast to UAssetThumbnailWidget manually (due to Unreal Header Tool restrictions).

Target is Asset Thumbnail Widget (Editor & Game)

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets the widget used for displaying in editor. Returns nullptr in non-editor builds.This type must be cast to UAssetThumbnailWidget manually (due to Unreal Header Tool restrictions). |
