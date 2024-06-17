---
title: Get AutoDestroySubsystem
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldSubsystems)

Get Auto Destroy Subsystem (World Subsystem)

The Auto destroy subsystem manages actors who have bAutoDestroyWhenFinished
set as true. This ensures that even actors who do not have Tick enabled
get properly destroyed, as well as decouple this behavior from AActor::Tick

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
