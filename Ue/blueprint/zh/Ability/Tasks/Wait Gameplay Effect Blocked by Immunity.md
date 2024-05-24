---
display_name: Wait Gameplay Effect Blocked by Immunity
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Listens for GE immunity. By default this means "this hero blocked a GE due to immunity". Setting OptionalExternalTarget will listen for a GE being blocked on an external target. Note this only works on the server.

Target is Ability Task Wait Gameplay Effect Blocked Immunity

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Source Tag Requirements |  |
| struct | Target Tag Requirements |  |
| object | Optional External Target |  |
| boolean | Only Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Blocked |  |
| struct | Blocked Spec |  |
| struct | Immunity Gameplay Effect Handle |  |
