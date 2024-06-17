---
title: Reset Databases to Search
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Motion Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/MotionMatching)

Clear the effects of SetDatabaseToSearch/SetDatabasesToSearch and resume searching the Database property on the motion matching node.

Target is Motion Matching Anim Node Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Motion Matching Node | The motion matching node to operate on. |
| enum | Interrupt Mode | mode to control the continuing pose search (the current animation that's playing) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
