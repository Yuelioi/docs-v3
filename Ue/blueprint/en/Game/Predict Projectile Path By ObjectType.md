---
title: Predict Projectile Path By ObjectType
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Predict the arc of a virtual projectile affected by gravity with collision checks along the arc. Returns a list of positions of the simulated arc and the destination reached by the simulation.
Returns true if it hit something.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start Pos | First start trace location |
| vector | Launch Velocity | Velocity the "virtual projectile" is launched at |
| boolean | Trace Path | Trace along the entire path to look for blocking hits |
| real | Projectile Radius | Radius of the virtual projectile to sweep against the environment |
| enum | Object Types | ObjectTypes to trace against, if bTracePath is true. |
| boolean | Trace Complex | Use TraceComplex (trace against triangles not primitives) |
| object | Actors to Ignore | Actors to exclude from the traces |
| enum | Draw Debug Type | Debug type (one-frame, duration, persistent) |
| real | Draw Debug Time | Duration of debug lines (only relevant for DrawDebugType::Duration) |
| real | Sim Frequency | Determines size of each sub-step in the simulation (chopping up MaxSimTime) |
| real | Max Sim Time | Maximum simulation time for the virtual projectile. |
| real | Override Gravity Z | Optional override of Gravity (if 0, uses WorldGravityZ) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Hit | Predicted hit result, if the projectile will hit something |
| vector | Out Path Positions | Predicted projectile path. Ordered series of positions from StartPos to the end. Includes location at point of impact if it hit something. |
| vector | Out Last Trace Destination | Goal position of the final trace it did. Will not be in the path if there is a hit. |
| boolean | Return Value | True if hit something along the path if tracing for collision. |
