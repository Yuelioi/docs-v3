---
title: Get Assets (Message)
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets asset data for all assets that match the filter.
Assets returned must satisfy every filter component if there is at least one element in the component's array.
Assets will satisfy a component if they match any of the elements in it.

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Filter | filter to apply to the assets in the AssetRegistry |
| boolean | Skip ARFiltered Assets | If true, skips Objects that return true for IsAsset but are not assets in the current platform. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Asset Data | the list of assets in this path |
| boolean | Return Value |  |
