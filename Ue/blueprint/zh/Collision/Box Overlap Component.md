---
title: Box Overlap Component
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Perform a box overlap against a single component as an AABB (No rotation)

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | In Box Centre | The centre of the box to overlap with the component |
| struct | In Box | Description of the box to use in the overlap |
| boolean | Trace Complex | Whether or not to trace the complex physics representation or just the simple representation |
| boolean | Show Trace | Whether or not to draw the trace in the world (for debugging) |
| boolean | Persistent Show Trace | Whether or not to make the debugging draw stay in the world permanently |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Hit Location |  |
| vector | Hit Normal |  |
| name | Bone Name |  |
| struct | Out Hit |  |
| boolean | Return Value |  |
