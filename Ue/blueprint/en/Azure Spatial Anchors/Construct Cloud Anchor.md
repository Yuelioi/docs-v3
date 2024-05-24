---
display_name: Construct Cloud Anchor
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Construct a cloud anchor for the pin. This is not yet stored in the cloud.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | ARPin | The ARPin to create an anchor for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Azure Cloud Spatial Anchor | The Cloud anchor handle. (null if fails) |
| enum | Out Result | The Result enumeration. |
| string | Out Error String | Additional informatiuon about the OutResult (often empty). |
