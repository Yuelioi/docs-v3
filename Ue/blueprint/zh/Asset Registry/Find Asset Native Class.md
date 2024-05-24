---
display_name: Find Asset Native Class
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Returns the first native class of the asset type that can be found. Normally this is just the FAssetData::GetClass(),
however if the class is a blueprint generated class it may not be loaded. In which case GetAncestorClassNames will
be used to find the first native super class. This can be slow if temporary caching mode is not on.

Target is Asset Registry Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Asset Data |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| class | Return Value | Returns the first native class of the asset type that can be found. Normally this is just the FAssetData::GetClass(),however if the class is a blueprint generated class it may not be loaded. In which case GetAncestorClassNames willbe used to find the first native super class. This can be slow if temporary caching mode is not on. |
