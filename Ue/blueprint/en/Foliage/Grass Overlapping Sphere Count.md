---
display_name: Grass Overlapping Sphere Count
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Foliage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Foliage)

Counts how many grass foliage instances overlap a given sphere.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Static Mesh |  |
| vector | Center Position | The center position of the sphere. |
| real | Radius | The radius of the sphere. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | Number of foliage instances with their mesh set to Mesh that overlap the sphere. |
