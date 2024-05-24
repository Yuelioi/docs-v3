---
display_name: Enumerate Audio Capture Devices
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Capture](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/Capture)

Enumerate available audio capture devices.

To filter for a specific subset of devices, use the MakeBitmask node
with EMediaAudioCaptureDeviceFilter as the Bitmask Enum.

Target is Media Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Filter | The types of capture devices to return (-1 = all). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Devices | Will contain the available capture devices. |
