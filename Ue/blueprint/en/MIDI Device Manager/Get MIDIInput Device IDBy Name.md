---
title: Get MIDIInput Device IDBy Name
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MIDI Device Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MIDIDeviceManager)

Retrieves the MIDI input device ID by name. Call "Find All MIDI Device Info" beforehand to enumerate the available input devices.

Target is MIDIDevice Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Device Name | The Name of the MIDI device you want to talk to. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Device ID | The Device ID of the MIDI device with that name. |
