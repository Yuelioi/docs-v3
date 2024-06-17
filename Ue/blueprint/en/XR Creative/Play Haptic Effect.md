---
title: Play Haptic Effect
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [XR Creative](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XRCreative)

Play haptic feedback asset on a given hand - only left and right supported

Target is XRCreative Avatar

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Haptic Effect | The haptic effect to play |
| integer | Controller ID | ID of PlayerController if in PIE or runtime (not required in-editor) |
| enum | Hand | Which hand to play the haptic effect on |
| real | Scale | Scale between 0.0 and 1.0 on the intensity of playback |
| boolean | Loop |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
