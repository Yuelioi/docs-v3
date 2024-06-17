---
title: Was Actor Recently Rendered
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Returns true if this actor has been rendered "recently", with a tolerance in seconds to define what "recent" means.
e.g.: If a tolerance of 0.1 is used, this function will return true only if the actor was rendered in the last 0.1 seconds of game time.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Tolerance | How many seconds ago the actor last render time can be and still count as having been "recently" rendered. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Whether this actor was recently rendered. |
