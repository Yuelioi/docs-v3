---
display_name: Make Reward from Direction Similarity
order: 220
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a reward based on how similar two directions are.

Target is Learning Agents Rewards

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Direction A | The first direction. |
| vector | Direction B | The second direction. |
| real | Reward Scale | The scale of the reward. Use a negative scale to create a penalty. |
| name | Tag | The tag for the reward. Used for debugging. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this reward. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this reward. |
| vector | Visual Logger Direction Location A | A location for the visual logger to display the first direction in the world. |
| vector | Visual Logger Direction Location B | A location for the visual logger to display the second direction in the world. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| real | Visual Logger Arrow Length | The length of the arrow to display for the directions. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | The resulting reward value. |
