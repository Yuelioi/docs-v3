---
title: Get Parent Sequence Frame
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Section](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Section)

Get the frame in the space of its parent sequence

Target is Movie Scene Section Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Section | The section that the InFrame is local to |
| integer | In Frame | The desired local frame |
| object | Parent Sequence | The parent sequence to traverse from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The frame at the parent sequence |
