---
display_name: Delete Cloud Anchor
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR/AzureSpatialAnchors)

Delete the cloud anchor in the cloud.
This will start a Latent Action to delete the cloud anchor from the cloud service.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Cloud Spatial Anchor | The Cloud anchor to delete. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| enum | Out Result | Result of the Delete attempt. |
| string | Out Error String | Additional information about the OutResult (often empty). |
