---
title: Get Portable Binding ID
order: 48
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

Get a portable binding ID for a binding that resides in a different sequence to the one where this binding will be resolved.
Note:: This function must be used over GetBindingID when the target binding resides in different shots or sub-sequences.
Note:: Only unique instances of sequences within a root sequences are supported

Target is Movie Scene Sequence Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Root Sequence | The root sequence that contains both the destination sequence (that will resolve the binding ID) and the target sequence that contains the actual binding |
| object | Destination Sequence | The sequence that will own or resolve the resulting binding ID. For example, if the binding ID will be applied to a camera cut section pass the sequence that contains the camera cut track to this parameter. |
| struct | In Binding |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The binding's id |
