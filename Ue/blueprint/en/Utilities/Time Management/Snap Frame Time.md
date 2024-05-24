---
display_name: Snap Frame Time
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Time Management](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/TimeManagement)

Snaps the given SourceTime to the nearest frame in the specified Destination Framerate. Useful for determining the nearest frame for another resolution. Returns the frame time in the destination frame rate.

Target is Time Management Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Source Time |  |
| struct | Source Rate |  |
| struct | Snap to Rate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Snaps the given SourceTime to the nearest frame in the specified Destination Framerate. Useful for determining the nearest frame for another resolution. Returns the frame time in the destination frame rate. |
