---
display_name: Get Last Movement Input Vector
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn/Input)

Return the last input vector in world space that was processed by ConsumeMovementInputVector(), which is usually done by the Pawn or PawnMovementComponent.
Any user that needs to know about the input that last affected movement should use this function.
For example an animation update would want to use this, since by default the order of updates in a frame is:
PlayerController (device input) -> MovementComponent -> Pawn -> Mesh (animations)

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | The last input vector in world space that was processed by ConsumeMovementInputVector(). |
