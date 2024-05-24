---
display_name: Get Loaded Level Names
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [World Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/WorldUtils)

Returns the path name (e.g. "/Game/Maps/MyLevel") of levels that are loaded on `World`.
We use these to revert the `World` to its initial state after we force-stream levels in for exporting

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | World |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | Returns the path name (e.g. "/Game/Maps/MyLevel") of levels that are loaded on `World`.We use these to revert the `World` to its initial state after we force-stream levels in for exporting |
