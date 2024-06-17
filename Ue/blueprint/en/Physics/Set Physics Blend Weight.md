---
title: Set Physics Blend Weight
order: 52
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

This is global set up for setting physics blend weight
This does multiple things automatically
If PhysicsBlendWeight == 1.f, it will enable Simulation, and if PhysicsBlendWeight == 0.f, it will disable Simulation.
Also it will respect each body's setup, so if the body is fixed, it won't simulate. Vice versa
So if you'd like all bodies to change manually, do not use this function, but SetAllBodiesPhysicsBlendWeight

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Physics Blend Weight |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
