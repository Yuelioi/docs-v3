---
title: Landed Delegate
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Character](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Character)

Called upon landing when falling, to perform actions based on the Hit result.
Note that movement mode is still "Falling" during this event. Current Velocity value is the velocity at the time of landing.
Consider OnMovementModeChanged() as well, as that can be used once the movement mode changes to the new mode (most likely Walking).

@param Hit Result describing the landing that resulted in a valid landing spot.
@see OnMovementModeChanged()
