---
display_name: Paste Prims
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Prim Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/PrimUtils)

Pastes the prims from the clipboard stage as children of ParentPrim.

The pasted prims may be renamed in order to have valid names for the target location, which is why this function
returns the pasted prim paths.
This function returns just paths instead of actual prims because USD needs to respond to the notices about
the created prim specs before the prims are fully created, which means we wouldn't be able to return the
created prims yet, in case this function was called from within an SdfChangeBlock.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Stage Root Layer | Path to the root layer of the stage from which we should fetch the Prims |
| string | Parent Prim Path | Prim that will become parent to the pasted prims |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | Paths to the pasted prim specs, after they were added as children of ParentPrim |
