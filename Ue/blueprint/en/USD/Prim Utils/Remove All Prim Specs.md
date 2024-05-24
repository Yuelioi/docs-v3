---
display_name: Remove All Prim Specs
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Prim Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/PrimUtils)

Removes all the prim specs for Prim on the given Layer.

This function is useful in case the prim is inside a variant set: In that case, just calling FUsdStage::RemovePrim()
will attempt to remove the "/Root/Example/Child", which wouldn't remove the "/Root{Varset=Var}Example/Child" spec,
meaning the prim may still be left on the stage. Note that it's even possible to have both of those specs at the same time:
for example when we have a prim inside a variant set, but outside of it we have overrides to the same prim. This function
will remove both.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Stage Root Layer | Path to the root layer of the stage from which we should fetch the Prims |
| string | Prim Path | Prim to remove |
| string | Target Layer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
