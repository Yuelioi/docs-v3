---
title: Get TargetingSubsystem
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game Instance Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameInstanceSubsystems)

Get Targeting Subsystem (GameInstance Subsystem)

@class UTargetingSubsystem

The Targeting Subsystem is the entry point for users to initiate targeting requests.

The entry point to the system is the target request handle. The handle is used to interface with
the targeting data stores. Data stores are templated classes around generic data structs that the
system and tasks use to accomplish a targeting request.

The targeting system has 3 mandatory data stores and 1 required for async targeting request. These
data stores are required to be set up before the system can properly run a targeting request. The
mandatory 3 data stores are FTargetingRequestData, FTargetingTaskSet, and FTargetingSourceContext.
FTargetingAsyncTaskData is implicitly setup when an async targeting request is initiated.

Users can do all the pieces manually in C++ by setting up the required data stores themselves,
or, to have it a bit more automated, the user can use the APIs that utilize UTargetingPreset data asset.

For immediate targeting requests users will call the Execute methods. These functions perform all the
tasks till completion. The system will not go latent.

For async targeting requests users will call the Start Async methods. The system will queue up a targeting
request and as each task is processed the system can run through all the tasks to completion or stop processing
until the next frame while it waits for a task to complete.

Note about Targeting Handles, when a targeting handle is created it will not implicitly release the handle.
It is up to the creator to either grab a Async Task Data or Immediate Task Data and set a flag indicating
the system should do it for them after the callback fires, or it is up to the user to release the handle
when they are done with it.

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
