---
title: Read Position Attribute
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraSimCache)

Reads Niagara Position attributes by name from the cache frame and appends them into the OutValues array.
Local space emitters provide data at local locations unless bLocalSpaceToWorld is true.
EmitterName - If left blank will return the system simulation attributes.
LocalSpaceToWorld - Caches are always stored in the emitters space, i.e. local or world space. You can set this to false if you want the local position rather than the world position.

Target is Niagara Sim Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Attribute Name |  |
| name | Emitter Name |  |
| boolean | Local Space to World |  |
| integer | Frame Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Values |  |
