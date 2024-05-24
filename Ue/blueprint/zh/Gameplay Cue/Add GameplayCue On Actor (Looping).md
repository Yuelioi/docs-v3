---
display_name: Add GameplayCue On Actor (Looping)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Cue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayCue)

Invoke the added event for a gameplay cue on the target actor. This should be paired with a RemoveGameplayCueOnActor call.

- If the actor has an ability system, the event will fire on authority only and will be replicated.
- If the actor does not have an ability system, the event will only be fired locally.

Target is Gameplay Cue Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Gameplay Cue Tag |  |
| struct | Parameters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
