---
title: Ignore Actor when Moving
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Tells this component whether to ignore collision with all components of a specific Actor when this component is moved.
Components on the other Actor may also need to be told to do the same when they move.
Does not affect movement of this component when simulating physics.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor |  |
| boolean | Should Ignore |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
