---
title: Constrain to Plane
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Ensures input Vector (typically a velocity, acceleration, or move delta) is limited to a movement plane.

Target is Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Vector |  |
| struct | Movement Plane |  |
| boolean | Maintain Magnitude | if true, vector will be scaled after projection in an attempt to keep magnitude the same |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Return Value |  |
