---
title: Get AR Candidate Object
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AugmentedReality)

Saves the point cloud centered at the specified location capturing all of the features within the specified extent as an object that can be detected later

Target is ARGet Candidate Object Async Task Blueprint Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Location | the center of the extent to grab features at |
| vector | Extent | the size of the region to grab feature points |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success |  |
| exec | On Failed |  |
| object | Saved Object |  |
