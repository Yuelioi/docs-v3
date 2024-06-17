---
title: Run Training
order: 260
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Convenience function that runs a basic training loop. If training has not been started, it will start it, and
then call RunInference. On each following call to this function, it will call GatherRewards,
GatherCompletions, and ProcessExperience, followed by RunInference.

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
| boolean | Reset Agents on Update | If true, reset all agents whenever an updated policy is received. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
