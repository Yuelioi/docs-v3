---
display_name: Get Desired Value
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Extractor Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionExtractorUtility)

Returns the desired value from the extracted poses based on input settings.

Target is Motion Extractor Utility Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| transform | Bone Transform | Current frame's bone transform |
| transform | Last Bone Transform | Last frame's bone transform. Unused when not calculating speeds. |
| real | Delta Time | Time step used between current and last bone transforms. Unused when not calculating speeds. |
| enum | Motion Type | What type of motion to extract (translation, rotation, speed, etc.) |
| enum | Axis | Which axis/axes to extract motion from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value |  |
