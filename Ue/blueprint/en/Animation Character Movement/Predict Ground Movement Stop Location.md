---
title: Predict Ground Movement Stop Location
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Character Movement](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationCharacterMovement)

Predict where the character will stop based on its current movement properties and parameters from the movement component.
This uses prediction logic that is heavily tied to the UCharacterMovementComponent.
Each parameter corresponds to a value from the UCharacterMovementComponent with the same name.
Because this is a thread safe function, it's recommended to populate these fields via the Property Access system.

Target is Anim Character Movement Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Velocity |  |
| boolean | Use Separate Braking Friction |  |
| real | Braking Friction |  |
| real | Ground Friction |  |
| real | Braking Friction Factor |  |
| real | Braking Deceleration Walking |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | The predicted stop position in local space to the character. The size of this vector will be the distance to the stop location. |
