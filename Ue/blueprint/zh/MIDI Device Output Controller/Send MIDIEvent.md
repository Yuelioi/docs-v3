---
title: Send MIDIEvent
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MIDI Device Output Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MIDIDeviceOutputController)

Sends MIDI event raw data for an event type

Target is MIDIDevice Output Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Event Type | The event type as specified in the EMIDIEventType struct |
| integer | Channel | The MIDI channel to send |
| integer | Data 1 | The first part of the MIDI data |
| integer | Data 2 | The second part of the MIDI data |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
