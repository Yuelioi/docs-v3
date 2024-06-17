---
title: Set Start Position
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Sequences](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Sequences)

Set the start position of the sequence player.
If this is called from On Become Relevant or On Initial Update then it should be accompanied by a call to
SetAccumulatedTime to achieve the desired effect of resetting the play time of a sequence player.

Target is Sequence Player Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Sequence Player |  |
| real | Start Position |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Set the start position of the sequence player.If this is called from On Become Relevant or On Initial Update then it should be accompanied by a call toSetAccumulatedTime to achieve the desired effect of resetting the play time of a sequence player. |
