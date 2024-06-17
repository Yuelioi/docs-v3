---
title: Refresh Cloud Anchor Properties
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Get the latest cloud anchor properties from the cloud.
This will start a Latent Action to fetch the AzureCloudSpatialAnchor's propertiesfrom the Azure Spatial Anchors cloud service.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Azure Cloud Spatial Anchor | The AzureCloudSpatialAnchor to refresh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| enum | Out Result | The Result enumeration. |
| string | Out Error String | Additional information about the OutResult (often empty). |
