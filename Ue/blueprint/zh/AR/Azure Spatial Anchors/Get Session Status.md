---
display_name: Get Session Status
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR/AzureSpatialAnchors)

Get the AzureSpatialAnchors Session's Status.
This will start a Latent Action to get the Session Status.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
| struct | Out Status | The retrieved status struct. |
| enum | Out Result | Result of the Save attempt. |
| string | Out Error String | Additional information about the OutResult (often empty). |
