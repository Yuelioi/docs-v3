---
display_name: Add Control to Set
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Adds a Control to a Set. This will add a new set if necessary. For example, you might
make a set of Controls called "ParentSpace_Feet" by calling this twice, passing in the left and right
foot ParentSpace controls.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Control |  |
| name | Set |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Set |  |
