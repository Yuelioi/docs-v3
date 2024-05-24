---
display_name: Get Gaze Data
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Eye Tracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EyeTracking)

Returns unfied gaze data from the eye tracker. This is a single gaze ray, representing the fusion of both eyes.

Target is Eye Tracker Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Gaze Data |  |
| boolean | Return Value | True if the returned gaze data is valid, false otherwise. A false return is likely to be common (e.g. the when user blinks). |
