---
display_name: Get Path Name for Loaded Asset
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Return a valid AssetPath for a loaded asset. The asset need to be a valid asset in the Content Browser.
Similar to GetPathName(). The format will be: /Game/MyFolder/MyAsset.MyAsset

Target is Editor Asset Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Loaded Asset | Loaded Asset that exist in the Content Browser. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | If valid, the asset Path of the loaded asset. |
