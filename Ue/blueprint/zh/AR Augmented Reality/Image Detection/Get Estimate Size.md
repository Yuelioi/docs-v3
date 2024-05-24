---
display_name: Get Estimate Size
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Image Detection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/ImageDetection)

- Get the estimate size of the detected image, where X is the estimated width, and Y is the estimated height.
  \*
- Note that ARCore can return a valid estimate size of the detected image when the tracking state of the UARTrackedImage
- is tracking. The size should reflect the actual size of the image target, which could be different than the input physical
- size of the candidate image.
  \*
- ARKit will return the physical size of the ARCandidate image.

Target is ARTracked Image

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | * Get the estimate size of the detected image, where X is the estimated width, and Y is the estimated height. **Note that ARCore can return a valid estimate size of the detected image when the tracking state of the UARTrackedImage *is tracking. The size should reflect the actual size of the image target, which could be different than the input physical* size of the candidate image.** ARKit will return the physical size of the ARCandidate image. |
