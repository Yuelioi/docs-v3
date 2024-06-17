---
title: Get Input Device Connection State
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Platform Input Device](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PlatformInputDevice)

Gets the connection state of the given input device.

Target is Input Device Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Device Id | The device to get the connection state of |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | Return Value | The connection state of the given device. EInputDeviceConnectionState::Unknown if the device is not mapped |
