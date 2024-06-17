---
title: Get Estimated Discounted Return
order: 65
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Gets an estimate of the average discounted return expected by an agent according to the critic. I.E. the total
sum of future rewards, scaled by the discount factor that was used during training. This value can be useful if
you want to make some decision based on how well the agent thinks they are doing at achieving their task. This
should be called only after EvaluateCritic.

Target is Learning Agents Critic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Agent Id | The AgentId to look-up the estimated discounted return for |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | The estimated average discounted return according to the critic |
