---
title: Get Streaming Source Location and Rotation
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Partition](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldPartition)

Gets the streaming source location and rotation.
Default implementation returns APlayerController::GetPlayerViewPoint but can be overriden in child classes.

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Location |  |
| rotator | Out Rotation |  |
