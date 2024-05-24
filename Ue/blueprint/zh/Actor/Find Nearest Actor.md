---
display_name: Find Nearest Actor
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Actor)

Returns an Actor nearest to Origin from ActorsToCheck array.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Origin | World Location from which the distance is measured. |
| object | Actors to Check | Array of Actors to examine and return Actor nearest to Origin. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Distance | Distance from Origin to the returned Actor. |
| object | Return Value | Nearest Actor. |
