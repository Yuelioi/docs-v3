---
title: Make Reward from Velocity Along Spline
order: 224
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a reward based on the velocity an object is moving along a spline.

Target is Learning Agents Rewards

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Spline Component | The spline. |
| vector | Location | The location of the object. |
| vector | Velocity | The velocity of the object. |
| real | Velocity Scale | The expected scale for the velocity. |
| real | Reward Scale | The scale of the reward. Use a negative scale to create a penalty. |
| real | Finite Difference Delta | The finite difference to use when computing the velocity along the spline. |
| name | Tag | The tag for the reward. Used for debugging. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this reward. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this reward. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | The resulting reward value. |
