---
title: Find Package Referencers for Asset
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Find Package Referencers for an asset. Only Soft and Hard dependencies would be looked for.
Soft are dependencies which don't need to be loaded for the object to be used.
Had are dependencies which are required for correct usage of the source asset and must be loaded at the same time.
Other references may exist. The asset may be currently used in memory by another asset, by the editor or by code.
Package dependencies are cached with the asset. False positive can happen until all the assets are loaded and re-saved.

Target is Editor Asset Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Asset Path | Asset Path of the asset that we are looking for (that is not a level). |
| boolean | Load Assets to Confirm | The asset and the referencers will be loaded (if not a level) to confirm the dependencies. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | The package path of the referencers. |
