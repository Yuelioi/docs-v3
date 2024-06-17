---
title: Add Body Modifiers to Set
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Adds BodyModifiers to a Set. This will add a new set if necessary. For example, you might
make a set of Arm body modifiers by calling this twice, passing in the left and right
arm body modifiers.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Body Modifiers |  |
| name | Set |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Set |  |
