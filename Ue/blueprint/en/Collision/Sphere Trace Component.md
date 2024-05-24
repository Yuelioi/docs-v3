---
display_name: Sphere Trace Component
order: 78
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Perform a sphere trace against a single component

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Trace Start | The start of the trace in world-space |
| vector | Trace End | The end of the trace in world-space |
| real | Sphere Radius | Radius of the sphere to trace against the component |
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
