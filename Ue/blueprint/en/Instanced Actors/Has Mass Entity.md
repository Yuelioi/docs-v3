---
title: Has Mass Entity
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Instanced Actors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/InstancedActors)

Returns true if this Actor was spawned by the Instanced Actor system for a Mass Entity.
On servers, MassEntityHandle will be set in UInstancedActorsComponent::InitializeComponent (before component BeginPlay)
On clients, MassEntityHandle will be set after component BeginPlay, as the link between Entity \<-> Actor isn't made until
both the actor has replicated to the client (recieving BeginPlay in the process) *and* the client Mass simulation attempts
to spawn an actor itself, whereupon the replicated actor is then returned for the client spawn request.

Target is Instanced Actors Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if this Actor was spawned by the Instanced Actor system for a Mass Entity.On servers, MassEntityHandle will be set in UInstancedActorsComponent::InitializeComponent (before component BeginPlay)On clients, MassEntityHandle will be set after component BeginPlay, as the link between Entity \<-> Actor isn't made untilboth the actor has replicated to the client (recieving BeginPlay in the process) *and* the client Mass simulation attemptsto spawn an actor itself, whereupon the replicated actor is then returned for the client spawn request. |
