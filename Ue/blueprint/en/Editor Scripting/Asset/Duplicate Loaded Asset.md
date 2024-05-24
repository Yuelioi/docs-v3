---
display_name: Duplicate Loaded Asset
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Duplicate an asset from the Content Browser that is already loaded. Will try to checkout the file.

Target is Editor Asset Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Source Asset | Asset that we want to copy from. |
| string | Destination Asset Path | Asset Path of the duplicated asset. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The duplicated object if the operation succeeds |
