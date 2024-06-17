---
title: Has Training Failed
order: 137
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Returns true if the trainer has failed to communicate with the external training process. This can be used in
combination with RunTraining to avoid filling the logs with errors.

Target is Learning Agents Trainer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the training has failed. Otherwise, false. |
