---
display_name: Get ColorCorrectRegionsSubsystem
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldSubsystems)

Get Color Correct Regions Subsystem (World Subsystem)

World Subsystem responsible for managing AColorCorrectRegion classes in level.
This subsystem handles:
Level Loaded, Undo/Redo, Added to level, Removed from level events.
Unfortunately AActor class itself is not aware of when it is added/removed, Undo/Redo etc in the level.

This is the only way (that we found) that was handling all region aggregation cases in more or less efficient way.
Covered cases: Region added to a level, deleted from level, level loaded, undo, redo, level closed, editor closed:
World subsystem keeps track of all Regions in a level via three events OnLevelActorAdded, OnLevelActorDeleted, OnLevelActorListChanged.
Actor classes are unaware of when they are added/deleted/undo/redo etc in the level, therefore this is the best place to manage this.
Alternative strategies (All tested):
World's AddOnActorSpawnedHandler. Flawed. Invoked in some cases we don't need, but does not get called during UNDO/REDO
AActor's PostSpawnInitialize, PostActorCreated and OnConstruction are also flawed.
AActor does not have an internal event for when its deleted (EndPlay is the closest we have).

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
