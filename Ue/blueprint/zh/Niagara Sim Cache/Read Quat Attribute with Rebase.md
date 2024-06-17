---
title: Read Quat Attribute with Rebase
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraSimCache)

Reads Niagara Quaternion attributes by name from the cache frame and appends them into the OutValues array.
Only attributes that in the rebase list will be transform into the provided Quat space. Therefore the cache
must be captured with rebasing enabled to have any impact.
EmitterName - If left blank will return the system simulation attributes.

Target is Niagara Sim Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Quat |  |
| name | Attribute Name |  |
| name | Emitter Name |  |
| integer | Frame Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Values |  |
