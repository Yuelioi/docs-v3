---
title: Begin Training
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Begins the training process with the provided settings.

Target is Learning Agents Trainer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Trainer Training Settings | The settings for this training run. |
| struct | Trainer Game Settings | The settings that will affect the game's simulation. |
| struct | Trainer Path Settings | The path settings used by the trainer. |
| boolean | Reset Agents on Begin | If true, reset all agents at the beginning of training. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
