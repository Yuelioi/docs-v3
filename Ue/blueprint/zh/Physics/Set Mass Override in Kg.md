---
title: Set Mass Override in Kg
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Override the mass (in Kg) of a single physics body.
Note that in the case where multiple bodies are attached together, the override mass will be set for the entire group.
Set the Override Mass to false if you want to reset the body's mass to the auto-calculated physx mass.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone Name |  |
| real | Mass in Kg |  |
| boolean | Override Mass |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
