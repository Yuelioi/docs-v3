---
display_name: Create Watcher
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Create and start a 'Watcher' searching for azure cloud spatial anchors as specified in the locate criteria. Use an AzureSpatialAnchorsEventComponent's events to get
notifications of found anchors and watcher completion.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Locate Criteria | Structure describing the watcher we wish to start. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Out Watcher Identifier | The ID of the created watcher (can be used to stop the watcher). |
| enum | Out Result | The Result enumeration. |
| string | Out Error String | Additional information about the OutResult (often empty). |
