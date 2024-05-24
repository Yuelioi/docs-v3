---
display_name: Make Velocity Observation
order: 247
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a new velocity observation.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | The Observation Object |
| vector | Velocity | The velocity of interest to the agent. |
| transform | Relative Transform | The transform the provided velocity should be encoded relative to. |
| real | Velocity Scale | Used to normalize the data for this observation. |
| name | Tag | The tag of the corresponding observation. Must match the tag given during Specify. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this observation. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this observation. |
| vector | Visual Logger Velocity Location | A location for the visual logger to display the velocity in the world. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation object element. |
