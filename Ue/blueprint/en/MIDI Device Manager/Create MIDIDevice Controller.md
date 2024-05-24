---
display_name: Create MIDIDevice Controller
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MIDI Device Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MIDIDeviceManager)

Creates an instance of a MIDI device controller that can be used to interact with a connected MIDI device

Target is MIDIDevice Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Device ID | The ID of the MIDI device you want to talk to. Call "Find MIDI Devices" to enumerate the available devices. |
| integer | MIDIBuffer Size | How large the buffer size (in number of MIDI events) should be for incoming MIDI data. Larger values can incur higher latency costs for incoming events, but don't set it too low or you'll miss events and your stuff will sound bad. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | If everything goes okay, a valid MIDI device controller object will be returned. If anything goes wrong, a null reference will be returned. |
