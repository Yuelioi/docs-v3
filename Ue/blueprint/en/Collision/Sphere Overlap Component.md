---
display_name: Sphere Overlap Component
order: 74
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Perform a sphere overlap against a single component

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | In Sphere Centre | The centre of the sphere to overlap with the component |
| real | In Sphere Radius | The Radius of the sphere to overlap with the component |
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
