---
display_name: Set Expiration
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Set the Expiration time of the cloud anchor as seconds into the future. You must call SaveCloudAnchor or UpdateCloudAnchorProperties before this will be persisted on azure.

Target is Azure Cloud Spatial Anchor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Lifetime |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
