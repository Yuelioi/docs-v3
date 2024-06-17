---
title: Detect Faces
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Apple Vision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AppleVision)

Detects faces within an image

Target is Apple Vision Detect Faces Async Task Blueprint Proxy

Latent. This node will complete at a later time. Latent nodes can only be placed in event graphs.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Source Image | the image to detect faces in |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success |  |
| exec | On Failure |  |
| struct | Face Detection Result |  |
