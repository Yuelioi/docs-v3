---
display_name: Acquire Data Registry Item (experimental)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataRegistry)

Starts an asynchronous acquire of a data registry item that may not yet be cached.

Target is Data Registry Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Item Id | Item identifier to lookup in cache |
| delegate | Acquire Callback | Delegate that will be called after acquire succeeds or failed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if request was started, false on unrecoverable error |
