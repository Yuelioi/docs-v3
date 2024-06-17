---
title: Save Pin to Cloud
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR/AzureSpatialAnchors)

Save the pin to the cloud.
This will start a Latent Action to save the ARPin to the Azure Spatial Anchors cloud service.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | ARPin | The ARPin to save. |
| real | Lifetime | The lifetime time of the cloud pin in the cloud in seconds. \<= 0 means no expiration. I would not expect expiration to be accurate to the second. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| object | Out Azure Cloud Spatial Anchor | The Cloud anchor handle. |
| enum | Out Result | Result of the Save attempt. |
| string | Out Error String | Additional information about the OutResult (often empty). |
