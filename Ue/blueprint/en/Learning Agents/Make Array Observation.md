---
title: Make Array Observation
order: 156
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a new array observation.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | The Observation Object |
| struct | Elements | The sub-observations. The number of elements here must be less than or equal to the maximum that was given during Specify. |
| integer | Max Num | The maximum number of elements possible for this observation. Must match what was given during Specify. |
| name | Tag | The tag of the corresponding observation. Must match the tag given during Specify. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation object element. |
