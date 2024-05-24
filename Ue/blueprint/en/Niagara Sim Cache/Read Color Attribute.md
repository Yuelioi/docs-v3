---
display_name: Read Color Attribute
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraSimCache)

Reads Niagara Color attributes by name from the cache frame and appends them into the OutValues array.
EmitterName - If left blank will return the system simulation attributes.

Target is Niagara Sim Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Attribute Name |  |
| name | Emitter Name |  |
| integer | Frame Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| linearcolor | Out Values |  |
