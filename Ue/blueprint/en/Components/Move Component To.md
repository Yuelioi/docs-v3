---
title: Move Component To
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components)

- Interpolate a component to the specified relative location and rotation over the course of OverTime seconds.
  \*

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Move | Move to target over specified time. |
| exec | Stop | If currently moving, stop. |
| exec | Return | If currently moving, return to where you started, over the time elapsed so far. |
| object | Component | Component to interpolate * |
| vector | Target Relative Location | Relative target location * |
| rotator | Target Relative Rotation | Relative target rotation * |
| boolean | Ease Out | if true we will ease out (ie end slowly) during interpolation * |
| boolean | Ease In | if true we will ease in (ie start slowly) during interpolation * |
| real | Over Time | duration of interpolation * |
| boolean | Force Shortest Rotation Path | if true we will always use the shortest path for rotation * |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
