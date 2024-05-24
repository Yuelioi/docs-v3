---
display_name: Get Center Of Mass
order: 68
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Get the center of mass of a single body. In the case of a welded body this will return the center of mass of the entire welded body (including its parent and children)
Objects that are not simulated return (0,0,0) as they do not have COM

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | If a SkeletalMeshComponent, name of body to get center of mass of. 'None' indicates root body. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value |  |
