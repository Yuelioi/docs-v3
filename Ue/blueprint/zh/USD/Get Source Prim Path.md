---
display_name: Get Source Prim Path
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD)

Gets the path to the prim that was parsed to generate the given `Object`.

Target is Usd Stage Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Object | UObject to query with. Can be one of the transient components generated when a stage was opened, or something like a UStaticMesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | The path to the source prim, e.g. "/root_prim/some_prim". May be empty in case we couldn't find the source prim. |
