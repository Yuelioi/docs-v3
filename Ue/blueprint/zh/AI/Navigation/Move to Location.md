---
title: Move to Location
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

Makes AI go toward specified Dest location, aborts any active path following

Target is AIController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Dest |  |
| real | Acceptance Radius | finish move if pawn gets close enough |
| boolean | Stop on Overlap | add pawn's radius to AcceptanceRadius |
| boolean | Use Pathfinding | use navigation data to calculate path (otherwise it will go in straight line) |
| boolean | Project Destination to Navigation | project location on navigation data before using it |
| boolean | Can Strafe | set focus related flag: bAllowStrafe |
| class | Filter Class | navigation filter for pathfinding adjustments. If none specified DefaultNavigationFilterClass will be used |
| boolean | Allow Partial Path | use incomplete path when goal can't be reached |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | Return Value |  |
