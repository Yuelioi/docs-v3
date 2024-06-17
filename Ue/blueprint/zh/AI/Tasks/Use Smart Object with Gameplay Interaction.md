---
title: Use Smart Object with Gameplay Interaction
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Tasks)

Helper function to create an AITask that interacts with the SmartObject slot using the GameplayInteraction definition.
This version will start the interaction on spot so the actor needs to be at the desired position.

Target is AITask Use Gameplay Interaction

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Controller | The controller that (or its attached pawn if available) will take part to the interaction. |
| struct | Claim Handle | The handle to an already claimed slot. |
| boolean | Lock AILogic | Indicates if the task adds UAIResource_Logic to the set of Claimed resources |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Finished |  |
| exec | On Succeeded |  |
| exec | On Failed |  |
| exec | On Move To Failed |  |
