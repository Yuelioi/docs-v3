---
title: Add Runtime Candidate Image
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/Session)

Create an ARCandidateImage object and add it to the ARCandidateImageList of the given \\c UARSessionConfig object.

Note that you need to restart the AR session with the \\c UARSessionConfig you are adding to to make the change take effect.

On ARCore platform, you can leave the PhysicalWidth to 0 if you don't know the physical size of the image or
the physical size is dynamic. And this function takes time to perform non-trivial image processing (20ms - 30ms),
and should be run on a background thread.

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Session Config |  |
| object | Candidate Texture |  |
| string | Friendly Name |  |
| real | Physical Width |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | A \\c UARCandidateImage Object pointer if the underlying ARPlatform added the candidate image at runtime successfully. Return nullptr otherwise. |
