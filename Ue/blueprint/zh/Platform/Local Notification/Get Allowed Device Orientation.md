---
display_name: Get Allowed Device Orientation
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform) > [Local Notification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Platform/LocalNotification)

Returns the allowed orientation of the device. This is NOT the same as GetDeviceOrientation, which only returns Portrait, LandscapeLeft,
PortraitUpsideDown or LandscapeRight. The allowed orientation limits what orientation your device can have. So if you set the allowed orientation
to LandscapeLeft, GetDeviceOrientation will only ever return LandscapeLeft. But if you set the allowed orientation to LandscapeSensor, you are actually
restricting the allowed orientations to LandscapeLeft OR LandscapeRight (depending on the sensor), so GetDeviceOrientation might return LandscapeLeft OR LandscapeRight.

Target is Blueprint Platform Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| enum | Return Value | An EDeviceScreenOrientation value. |
