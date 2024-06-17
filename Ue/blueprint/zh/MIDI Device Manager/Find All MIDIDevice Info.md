---
title: Find All MIDIDevice Info
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MIDI Device Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MIDIDeviceManager)

Enumerates all of the MIDI input and output devices and reports back useful infos such as IDs and names of those devices. This operation is a little expensive
so only do it once at startup, or if you think that a new device may have been connected.

Target is MIDIDevice Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out MIDIInput Devices | A list of available MIDI Input devices |
| struct | Out MIDIOutput Devices | A list of available MIDI Output devices |
