---
title: Async Load Primary Asset Class List
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetManager)

Load a list of primary asset classes into memory, this will cause them to stay loaded until explicitly unloaded.
The completed event will happen when the load succeeds or fails, and the Loaded list will contain all of the requested classes found at completion.
If LoadBundles is specified, those bundles are loaded along with the assets.

Target is Async Action Load Primary Asset Class List

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Primary Asset List |  |
| name | Load Bundles |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | Completed |  |
| class | Loaded |  |
