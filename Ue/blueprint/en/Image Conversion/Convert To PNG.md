---
display_name: Convert To PNG
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Image Conversion](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ImageConversion)

Converts a image to an array of TIFF data in a background task

Target is Apple Image Utils Base Async Task Blueprint Proxy

Latent. This node will complete at a later time. Latent nodes can only be placed in event graphs.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Source Image | the image to compress |
| boolean | Want Color | whether the PNG is color (true) or monochrome (false) |
| boolean | Use Gpu | whether to use the GPU (true) or the CPU (false) to compress |
| real | Scale | whether to scale the image before conversion, defaults to no scaling |
| enum | Rotate | a direction to rotate the image in during conversion, defaults to none |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success |  |
| exec | On Failure |  |
| struct | Conversion Result |  |
