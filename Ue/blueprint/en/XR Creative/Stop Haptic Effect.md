---
display_name: Stop Haptic Effect
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [XR Creative](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XRCreative)

Instantly stop a haptic feedback for a given hand - only left and right supported

Target is XRCreative Avatar

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Hand | Which hand to stop the haptic effect on |
| integer | Controller ID | ID of PlayerController if in PIE or runtime (not required in-editor) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
