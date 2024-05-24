---
display_name: Checkout Directory
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Checkout assets from the Content Browser. It will load the assets if needed.
All objects that are in the directory will be checkout. Assets will be loaded before being checkout.

Target is Editor Asset Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Directory Path | Directory of the assets that to checkout. |
| boolean | Recursive | If the AssetPath is a folder, the search will be recursive and will checkout the asset in the sub folders. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |
