---
title: On Target Perception Forgotten
order: 165
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

Notifies all bound delegates that the perception info has been forgotten for a given target.
The notification get broadcast when all stimuli of a given target expire. Note that this
functionality requires the the actor forgetting must be enabled via AIPerceptionSystem.bForgetStaleActors.

@param SourceActor Actor associated to the stimulus (can not be null)
@param Stimulus Updated stimulus
