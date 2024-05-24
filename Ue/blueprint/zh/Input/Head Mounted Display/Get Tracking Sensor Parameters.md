---
display_name: Get Tracking Sensor Parameters
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

If the HMD has a positional sensor, this will return the game-world location of it, as well as the parameters for the bounding region of tracking.
This allows an in-game representation of the legal positional tracking range. All values will be zeroed if the sensor is not available or the HMD does not support it.

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Index | (in) Index of the tracking sensor to query |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Origin | (out) Origin, in world-space, of the sensor |
| rotator | Rotation | (out) Rotation, in world-space, of the sensor |
| real | Left FOV | (out) Field-of-view, left from center, in degrees, of the valid tracking zone of the sensor |
| real | Right FOV | (out) Field-of-view, right from center, in degrees, of the valid tracking zone of the sensor |
| real | Top FOV | (out) Field-of-view, top from center, in degrees, of the valid tracking zone of the sensor |
| real | Bottom FOV | (out) Field-of-view, bottom from center, in degrees, of the valid tracking zone of the sensor |
| real | Distance | (out) Nominal distance to sensor, in world-space |
| real | Near Plane | (out) Near plane distance of the tracking volume, in world-space |
| real | Far Plane | (out) Far plane distance of the tracking volume, in world-space |
| boolean | Is Active | (out) True, if the query for the specified sensor succeeded. |
