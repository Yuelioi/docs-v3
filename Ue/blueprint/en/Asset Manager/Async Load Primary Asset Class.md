---
display_name: Async Load Primary Asset Class
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetManager)

Load a primary asset class into memory, this will cause it to stay loaded until it is explicitly unloaded.
The completed event will happen when the load succeeds or fails, you should cast the Loaded class to verify it is the correct type.
If LoadBundles is specified, those bundles are loaded along with the asset.

Target is Async Action Load Primary Asset Class

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Primary Asset |  |
| name | Load Bundles |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | Completed |  |
| class | Loaded |  |
