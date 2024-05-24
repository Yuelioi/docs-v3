---
display_name: Load Cloud Anchor
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR/AzureSpatialAnchors)

Load a pin from the cloud..
This will start a Latent Action to load a cloud anchor and create a pin for it.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Cloud Identifier | The Azure Cloud Spatial Anchor Identifier of the cloud anchor we will try to load. |
| string | Pin Id | Specify the name of the Pin to load into. Will fail if a pin of this name already exists. If empty an auto-generated id will be used. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| object | Out ARPin | Filled in with the pin created, if successful. |
| object | Out Azure Cloud Spatial Anchor | Filled in with the UE representation of the cloud spatial anchor created, if successful. |
| enum | Out Result | The Result enumeration. |
| string | Out Error String | Additional informatiuon about the OutResult (often empty). |
