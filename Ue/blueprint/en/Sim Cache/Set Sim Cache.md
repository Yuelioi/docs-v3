---
title: Set Sim Cache
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SimCache)

Sets the simulation cache to use for the component.
A null SimCache parameter will clear the active simulation cache.
When clearing a simulation cache that has been running you may wish to reset or continue, this option is only
valid when using a full simulation cache. A renderer only cache will always reset as we can not continue the
simulation due to missing simulation data.

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Sim Cache |  |
| boolean | Reset System |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
