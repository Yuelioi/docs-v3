---
display_name: Get Actors in Selection Rectangle
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Returns the array of actors inside a selection rectangle, with a class filter.

Sample usage:

TArray ActorsInSelectionRect;
Canvas->GetActorsInSelectionRectangle(FirstPoint,SecondPoint,ActorsInSelectionRect);

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| class | Class Filter |  |
| vector2d struct | First Point | The first point, or anchor of the marquee box. Where the dragging of the marquee started in screen space. |
| vector2d struct | Second Point | The second point, where the mouse cursor currently is / the other point of the box selection, in screen space. |
| boolean | Include Non Colliding Components | Whether to include even non-colliding components of the actor when determining its bounds |
| boolean | Actor Must be Fully Enclosed | The Selection rule: whether the selection box can partially intersect Actor, or must fully enclose the Actor. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Out Actors |  |
