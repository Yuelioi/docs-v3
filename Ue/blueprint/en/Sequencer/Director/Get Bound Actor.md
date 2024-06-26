---
title: Get Bound Actor
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Director](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Director)

Resolve the first valid Actor binding inside this sub-sequence that relates to the specified ID
Note:: ObjectBinding should be constructed from the same sequence as this Sequence Director's owning Sequence (see the GetSequenceBinding node)

Target is Level Sequence Director

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Object Binding | The ID for the object binding inside this sub-sequence or one of its children to resolve |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
