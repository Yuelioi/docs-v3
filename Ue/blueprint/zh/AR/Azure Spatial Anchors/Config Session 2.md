---
title: Config Session 2
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR/AzureSpatialAnchors)

Configure the ASA session.
This will take effect when the next session is started.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Session Configuration | Azure cloud sign in related configuration. |
| struct | Coarse Localization Settings | Settings related to locating the device in the world (eg GPS). |
| enum | Log Verbosity | Logging verbosity for the Azure Spatial Anchor api. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | (Boolean) True if the session configuration was set. |
