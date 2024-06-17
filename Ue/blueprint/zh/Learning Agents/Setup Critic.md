---
title: Setup Critic
order: 269
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Initializes a critic to be used with the given agent interactor and critic settings.

Target is Learning Agents Critic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Manager | The input Manager |
| object | In Interactor | The input Interactor object |
| object | In Policy | The input Policy object |
| object | Critic Neural Network Asset | Optional Network Asset to use. If not provided, asset is empty, or bReinitializeNetwork is set then a new neural network object will be created according to the given CriticSettings. |
| boolean | Reinitialize Critic Network | If to reinitialize the critic network |
| struct | Critic Settings | The critic settings to use on creation of a new critic network |
| integer | Seed | Random seed to use for initializing the critic weights |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
