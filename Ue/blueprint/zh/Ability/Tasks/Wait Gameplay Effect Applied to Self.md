---
display_name: Wait Gameplay Effect Applied to Self
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the owner *receives* a GameplayEffect from a given source (the source may be the owner too!). If TriggerOnce is true, this task will only return one time. Otherwise it will return everytime a GE is applied that meets the requirements over the life of the ability
Optional External Owner can be used to run this task on someone else (not the owner of the ability). By default you can leave this empty.

Target is Ability Task Wait Gameplay Effect Applied Self

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Source Filter |  |
| struct | Source Tag Requirements |  |
| struct | Target Tag Requirements |  |
| boolean | Trigger Once |  |
| object | Optional External Owner |  |
| boolean | Listen for Periodic Effect |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Applied |  |
| object | Source |  |
| struct | Spec Handle |  |
| struct | Active Handle |  |
