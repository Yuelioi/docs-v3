---
title: Setup Trainer
order: 273
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Initializes the trainer and runs the setup functions for rewards and completions.

Target is Learning Agents Trainer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Manager | The agent manager we are using. |
| object | In Interactor | The agent interactor we are training with. |
| object | In Policy | The policy to be trained. |
| object | In Critic | The critic to be trained. |
| struct | Trainer Settings | The trainer settings to use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
