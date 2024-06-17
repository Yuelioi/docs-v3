---
title: Save Cloud Anchor
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Save the cloud anchor to the cloud.
This will start a Latent Action to save the AzureCloudSpatialAnchor to the Azure Spatial Anchors cloud service.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Azure Cloud Spatial Anchor | The AzureCloudSpatialAnchor to save. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| enum | Out Result | The Result enumeration. |
| string | Out Error String | Additional information about the OutResult (often empty). |
