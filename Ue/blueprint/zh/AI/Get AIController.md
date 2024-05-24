---
display_name: Get AIController
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI)

The way it works exactly is if the actor passed in is a pawn, then the function retrieves
pawn's controller cast to AIController. Otherwise the function returns actor cast to AIController.

Target is AIBlueprint Helper Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Controlled Actor |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The way it works exactly is if the actor passed in is a pawn, then the function retrievespawn's controller cast to AIController. Otherwise the function returns actor cast to AIController. |
