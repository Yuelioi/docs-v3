---
title: Get Cached Bone Transforms
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Gets the transforms of the requested bones that will be used as targets (in world space). Targets for bones
that are not found will be set to Identity. Note that these targets will have been calculated and cached
at the start of the Physics Control Component, so if using the built in tick, may be too old to be useful.
If you manually update the component then you can access these target transforms prior to applying your
own targets.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component |  |
| name | Bone Names |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Return Value | Gets the transforms of the requested bones that will be used as targets (in world space). Targets for bonesthat are not found will be set to Identity. Note that these targets will have been calculated and cachedat the start of the Physics Control Component, so if using the built in tick, may be too old to be useful.If you manually update the component then you can access these target transforms prior to applying yourown targets. |
