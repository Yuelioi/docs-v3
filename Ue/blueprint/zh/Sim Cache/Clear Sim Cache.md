---
title: Clear Sim Cache
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SimCache)

Clear any active simulation cache.
When clearing a simulation cache that has been running you may wish to reset or continue, this option is only
valid when using a full simulation cache. A renderer only cache will always reset as we can not continue the
simulation due to missing simulation data.

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Reset System |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
