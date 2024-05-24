---
display_name: Add Asset Reference
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Adds a new UObject referencer to a particular asset, returning true if the operation succeeded.

Assets will not be evicted or removed from the cache while the referencer is registered.
Note that internally the cache keeps FObjectKey structs constructed from the referencers, instead of direct
pointers to them.

Target is USD Asset Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Asset |  |
| object | Referencer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Adds a new UObject referencer to a particular asset, returning true if the operation succeeded.Assets will not be evicted or removed from the cache while the referencer is registered.Note that internally the cache keeps FObjectKey structs constructed from the referencers, instead of directpointers to them. |
