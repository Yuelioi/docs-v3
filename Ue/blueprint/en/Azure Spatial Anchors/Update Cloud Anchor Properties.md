---
title: Update Cloud Anchor Properties
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Save the cloud anchor's properties to the cloud.
This will start a Latent Action to save the AzureCloudSpatialAnchor properties to the Azure Spatial Anchors cloud service.
This can fail if another client updates the anchor. If that happens you will have to call RefreshCloudAnchorProperties to get the updated values before you might UpdateCloudAnchorProperties sucessfully.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Azure Cloud Spatial Anchor | The AzureCloudSpatialAnchor to update. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| enum | Out Result | The Result enumeration. |
| string | Out Error String | Additional information about the OutResult (often empty). |
