---
display_name: Find MIDIDevices
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MIDI Device Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MIDIDeviceManager)

Enumerates all of the connected MIDI devices and reports back with the IDs and names of those devices. This operation is a little expensive
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
| struct | Out MIDIDevices | A list of available MIDI devices |
