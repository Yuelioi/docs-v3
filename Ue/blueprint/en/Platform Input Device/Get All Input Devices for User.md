---
title: Get All Input Devices for User
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Platform Input Device](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PlatformInputDevice)

Populates the OutInputDevices array with any InputDeviceID's that are mapped to the given platform user

Target is Input Device Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | User Id | The Platform User to gather the input devices of. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Input Devices | Array of input device ID's that will be populated with the mapped devices. |
| integer | Return Value | The number of mapped devices, INDEX_NONE if the user was not found. |
