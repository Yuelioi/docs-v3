---
title: Get Merged Asset User Data
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Customizable Object Instance](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CustomizableObjectInstance)

Returns the AssetUserData that was gathered from all the constituent mesh parts during the last update.
It requires that the CustomizableObject had the bEnableAssetUserDataMerge set to true during compilation.

Target is Customizable Object Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Component Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Returns the AssetUserData that was gathered from all the constituent mesh parts during the last update.It requires that the CustomizableObject had the bEnableAssetUserDataMerge set to true during compilation. |
