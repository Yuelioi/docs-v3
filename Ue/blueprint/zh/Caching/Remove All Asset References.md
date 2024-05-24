---
display_name: Remove All Asset References
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Removes the particular referencer to all assets tracked by the cache, if it was a referencer to any of them.
Returns true if at least one asset referencer count was altered by this.

Target is USD Asset Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Referencer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Removes the particular referencer to all assets tracked by the cache, if it was a referencer to any of them.Returns true if at least one asset referencer count was altered by this. |
