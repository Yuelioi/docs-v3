---
title: Set Emitter Fixed Bounds
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Sets the fixed bounds for an emitter instance, this overrides all other bounds.
The box is expected to be in local space not world space.
A default uninitialized box will clear the fixed bounds and revert back to emitter fixed / dynamic bounds.

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Emitter Name |  |
| struct | Local Bounds |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
