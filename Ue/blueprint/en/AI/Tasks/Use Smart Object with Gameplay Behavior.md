---
display_name: Use Smart Object with Gameplay Behavior
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Tasks)

Helper function to create an AITask that interacts with the SmartObject slot using the GameplayBehavior definition
This version starts the interaction on spot so the actor needs to be at the desired position.

Target is AITask Use Gameplay Behavior Smart Object

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Controller | The controller for which the attached pawn will take part to the GameplayBehavior. |
| struct | Claim Handle | The handle to an already claimed slot. |
| boolean | Lock AILogic | Indicates if the task adds UAIResource_Logic to the set of Claimed resources |
| enum | Claim Priority |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Succeeded |  |
| exec | On Failed |  |
| exec | On Move To Failed |  |
