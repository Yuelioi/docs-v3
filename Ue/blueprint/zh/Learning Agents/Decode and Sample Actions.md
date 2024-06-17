---
title: Decode and Sample Actions
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Decodes and samples action vectors using the Decoder network. This should be called after EvaluatePolicy and before PerformActions.

Target is Learning Agents Policy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Action Noise Scale | Scale of the action noise to use during sampling. Set this to zero to always sample the mean (expected) action. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
