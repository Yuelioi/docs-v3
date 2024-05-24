---
display_name: Stop Watcher
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Stop the specified Watcher looking for anchors, if it still exists.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | In Watcher Identifier | The identifier of the watcher we are trying to stop. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | (Boolean) True if the watcher existed. False if it did not. |
