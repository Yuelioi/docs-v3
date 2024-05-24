---
display_name: Play Root Motion Source
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation)

Callable by authority. Plays "out of band" animation: e.g, directly sets the RootMotionSourceID on the sync state, rather than the pending InputCmd.
This is analogous to outside code teleporting the actor (outside of the core simulation function)

Target is Mock Root Motion Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Source |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
