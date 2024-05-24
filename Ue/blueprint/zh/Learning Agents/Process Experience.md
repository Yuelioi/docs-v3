---
display_name: Process Experience
order: 249
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Call this function at the end of each step of your training loop. This takes the current observations/actions/
rewards and moves them into the episode experience buffer. All agents with full episode buffers or those which
have been signaled complete will be reset. If enough experience is gathered, it will be sent to the training
process and an iteration of training will be run and the updated policy will be synced back.

Target is Learning Agents Trainer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Reset Agents on Update | If true, reset all agents whenever an updated policy is received. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
