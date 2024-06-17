---
title: Get Pitch Scale from MIDIPitch
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sound Utilities BPLibrary](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SoundUtilitiesBPLibrary)

Calculates Pitch Scalar based on starting frequency and desired MIDI Pitch output

Target is Sound Utilities BPFunction Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Base Midi Note | The MIDI note corresponding to the starting frequency |
| integer | Target Midi Note | The MIDI note corresponding to the desired final frequency |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | The amount to scale the pitch of the base note by, in order for its pitch to match the target MIDI note |
