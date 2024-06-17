---
title: Get Orientation and Position
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

Grabs the current orientation and position for the HMD. If positional tracking is not available, DevicePosition will be a zero vector

Target is Head Mounted Display Function Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Device Rotation | (out) The device's current rotation |
| vector | Device Position | (out) The device's current position, in its own tracking space |
