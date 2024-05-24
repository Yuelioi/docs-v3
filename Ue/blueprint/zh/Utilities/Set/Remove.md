---
display_name: Remove
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Set)

Remove item from set. Output value indicates if something was actually removed. False
indicates no equivalent item was found.

Target is Blueprint Set Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| wildcard | Target Set | The set to remove from |
| wildcard | Item | The item to remove from the set |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if an item was removed (False indicates no equivalent item was present) |
