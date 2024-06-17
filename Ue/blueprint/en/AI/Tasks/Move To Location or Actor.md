---
title: Move To Location or Actor
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Tasks)

AIMove To

Target is AITask Move To

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Controller |  |
| vector | Goal Location |  |
| object | Goal Actor |  |
| real | Acceptance Radius |  |
| enum | Stop on Overlap |  |
| enum | Accept Partial Path |  |
| boolean | Use Pathfinding |  |
| boolean | Lock AILogic |  |
| boolean | Use Continuous Goal Tracking |  |
| enum | Project Goal on Navigation |  |
| enum | Require Navigable End Location |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Request Failed |  |
| exec | On Move Finished |  |
