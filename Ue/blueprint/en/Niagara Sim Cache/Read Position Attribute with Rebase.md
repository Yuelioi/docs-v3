---
title: Read Position Attribute with Rebase
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraSimCache)

Reads Niagara Position attributes by name from the cache frame and appends them into the OutValues array.
All attributes read with this method will be re-based from the captured space into the provided transform space,
this will occur even if the cache was not captured with re-basing enabled.
EmitterName - If left blank will return the system simulation attributes.

Target is Niagara Sim Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| transform | Transform |  |
| name | Attribute Name |  |
| name | Emitter Name |  |
| integer | Frame Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Values |  |
