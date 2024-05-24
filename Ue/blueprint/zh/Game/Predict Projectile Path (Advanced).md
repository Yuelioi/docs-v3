---
display_name: Predict Projectile Path (Advanced)
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Predict the arc of a virtual projectile affected by gravity with collision checks along the arc.
Returns true if it hit something.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Predict Params | Input params to the trace (start location, velocity, time to simulate, etc). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Predict Result | Output result of the trace (Hit result, array of location/velocity/times for each trace step, etc). |
| boolean | Return Value | True if hit something along the path (if tracing with collision). |
