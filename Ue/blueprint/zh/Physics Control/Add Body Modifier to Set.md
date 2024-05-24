---
display_name: Add Body Modifier to Set
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Adds a BodyModifier to a Set. This will add a new set if necessary. For example, you might
make a set of body modifiers called "Feet" by calling this twice, passing in the left and right
foot body modifiers.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Body Modifier |  |
| name | Set |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Set |  |
