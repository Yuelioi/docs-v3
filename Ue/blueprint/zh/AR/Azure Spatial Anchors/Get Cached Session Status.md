---
title: Get Cached Session Status
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR) > [Azure Spatial Anchors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AR/AzureSpatialAnchors)

Get the azure spatial anchors session status struct.

Target is Azure Spatial Anchors Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Status | The retrieved status struct. |
| boolean | Return Value | (Boolean&) True if is an AzureSpatialAnchors plugin running. False probably means that this platform does not support ASA or the plugin for this platform is not enabled. |
