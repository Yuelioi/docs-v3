---
display_name: Compute Angular Velocity
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Computes the angular velocity needed to change from one orientation to another within a time frame. Use the optional TurningRateLimit to clamp to a maximum step (negative=unlimited).

Target is Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| rotator | From |  |
| rotator | To |  |
| real | Delta Seconds |  |
| real | Turning Rate Limit |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| rotator | Return Value | Computes the angular velocity needed to change from one orientation to another within a time frame. Use the optional TurningRateLimit to clamp to a maximum step (negative=unlimited). |
