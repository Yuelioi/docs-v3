---
display_name: Remove Asset Reference
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Removes an UObject referencer from a particular asset, returning true if the operation succeeded.
If no specific Referencer is provided, all referencers to Asset will be removed.

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
| boolean | Return Value | Removes an UObject referencer from a particular asset, returning true if the operation succeeded.If no specific Referencer is provided, all referencers to Asset will be removed. |
