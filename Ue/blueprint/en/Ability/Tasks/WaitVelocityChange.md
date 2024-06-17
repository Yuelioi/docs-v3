---
title: WaitVelocityChange
order: 56
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait for the actor's movement component velocity to be of minimum magnitude when projected along given direction

Target is Ability Task Wait Velocity Change

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Direction |  |
| real | Minimum Magnitude |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Velocity Chage | Delegate called when velocity requirements are met |
