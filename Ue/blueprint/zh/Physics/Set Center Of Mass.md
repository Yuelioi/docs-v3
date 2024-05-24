---
display_name: Set Center Of Mass
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Set the center of mass of a single body. This will offset the physx-calculated center of mass.
Note that in the case where multiple bodies are attached together, the center of mass will be set for the entire group.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Center Of Mass Offset | User specified offset for the center of mass of this object, from the calculated location. |
| name | Bone Name | If a SkeletalMeshComponent, name of body to set center of mass of. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
