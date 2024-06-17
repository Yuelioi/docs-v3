---
title: Get MIDIOutput Device IDBy Name
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MIDI Device Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MIDIDeviceManager)

Retrieves the MIDI output device ID by name. Call "Find All MIDI Device Info" beforehand to enumerate the available output devices.

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
| integer | Device ID | The Device ID of the MIDI output device associated with that name. |
