---
display_name: Get Current Path
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI)

Returns a NEW UOBJECT that is a COPY of navigation path given controller is currently using.
The result being a copy means you won't be able to influence agent's pathfollowing
by manipulating received path.
Please use GetCurrentPathPoints if you only need the array of path points.

Target is AIBlueprint Helper Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Controller |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Returns a NEW UOBJECT that is a COPY of navigation path given controller is currently using.The result being a copy means you won't be able to influence agent's pathfollowingby manipulating received path.Please use GetCurrentPathPoints if you only need the array of path points. |
