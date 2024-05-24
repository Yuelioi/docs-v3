---
display_name: Get EnhancedInputWorldSubsystem
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldSubsystems)

Get Enhanced Input World Subsystem (Experimental) (World Subsystem)

Per world input subsystem that allows you to bind input delegates to actors without an owning Player Controller.
This should be used when an actor needs to receive input delegates but will never have an owning Player Controller.
For example, you can add input delegates to unlock a door when the user has a certain set of keys pressed.
Be sure to enable input on the actor, or else the input delegates won't fire!

Note: if you do have an actor with an owning Player Controller use the local player input subsystem instead.

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
