---
display_name: Create ARPin Around Azure Cloud Spatial Anchor
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AzureSpatialAnchors)

Create an ARPin around an already existing cloud anchor.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Pin Id | The name of the pin we want created. |
| object | In Azure Cloud Spatial Anchor | The cloud anchor we will create the pin around. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out ARPin | The pin that was created, or null. |
| boolean | Return Value | (Boolean) True if we were able to create. |
