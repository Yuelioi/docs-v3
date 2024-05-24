---
display_name: Wait Gameplay Event to Actor
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Async](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Async)

Wait until the specified gameplay tag event is triggered on a target ability system component
It will keep listening as long as OnlyTriggerOnce = false
If OnlyMatchExact = false it will trigger for nested tags
If used in an ability graph, this async action will wait even after activation ends. It's recommended to use WaitGameplayEvent instead.

Target is Ability Async Wait Gameplay Event

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Actor |  |
| struct | Event Tag |  |
| boolean | Only Trigger Once |  |
| boolean | Only Match Exact |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| exec | Event Received |  |
| struct | Payload |  |
