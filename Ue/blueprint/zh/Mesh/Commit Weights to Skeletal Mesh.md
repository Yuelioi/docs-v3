---
display_name: Commit Weights to Skeletal Mesh
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mesh)

Actually applies the weight modifications to the skeletal mesh. This action creates an undo transaction.
The skeletal mesh asset will be dirtied, but it is up to the user to save the asset if required.

Target is Skin Weight Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if weights were applied to a skeletal mesh, false otherwise |
