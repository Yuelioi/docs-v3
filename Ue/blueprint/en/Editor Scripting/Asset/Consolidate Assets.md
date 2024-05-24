---
display_name: Consolidate Assets
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Consolidates an asset by replacing all references/uses of the provided AssetsToConsolidate with references to AssetToConsolidateTo.
This is useful when you want all references of assets to be replaced by a single asset.
The function first attempts to directly replace all relevant references located within objects that are already loaded and in memory.
Next, it deletes the AssetsToConsolidate, leaving behind object redirectors to AssetToConsolidateTo.

Target is Editor Asset Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Asset to Consolidate To | Asset to which all references of the AssetsToConsolidate will instead refer to after this operation completes. |
| object | Assets to Consolidate | All references to these assets will be modified to reference AssetToConsolidateTo instead. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |
