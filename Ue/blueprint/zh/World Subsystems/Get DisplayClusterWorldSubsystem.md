---
title: Get DisplayClusterWorldSubsystem
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldSubsystems)

Get Display Cluster World Subsystem (World Subsystem)

World Subsystem used to react to level and world changes.
When Concert reloads the packages, streamed levels are removed and re-added without invoiking LoadMap which
circumvents FDisplayClusterGameManager::StartScene method invoked inside LoadMap method of DisplayClusterGameEngine.
This causes issues such as not updating references to DisplayClusterRootActor which causes memory corruption, crashes
and graphic corruption. This Subsystem is used to react to changes in number of levels used in the current world
and forces DisplayClusterModule to refresh all of its managers.

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
