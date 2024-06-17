---
title: Add Marked Frame
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

- Add a given user marked frame.
- A unique label will be generated if the marked frame label is empty
  \*
- @InMarkedFrame The given user marked frame to add
  \*

Target is Movie Scene Sequence Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sequence |  |
| struct | In Marked Frame |  |
| enum | Time Unit |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The index to the newly added marked frame |
