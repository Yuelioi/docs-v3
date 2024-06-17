---
title: Get Asset User Data Of Class
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset User Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetUserData)

Returns an instance of the provided AssetUserData class if it's contained in the target asset.

Target is Interface Asset User Data

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| class | In User Data Class | UAssetUserData sub class to get |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The instance of the UAssetUserData class contained, or null if it doesn't exist |
