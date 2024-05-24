---
display_name: Replace Unreal Materials with Baked
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Conversion Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ConversionUtils)

Traverses the context's stage and authors material binding attributes for all `unrealMaterials` that were baked into USD material assets.

Target is Usd Conversion Blueprint Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Layer to Author In | File path to the layer where the material binding opinions are authored |
| string | Baked Materials | Maps from material path names to file paths where they were baked Example: { "/Game/MyMaterials/Red.Red": "C:/MyFolder/Red.usda" } |
| boolean | Is Asset Layer | True when we're exporting a single mesh/animation asset. False when we're exporting a level. Dictates minor behaviors when authoring the material binding relationships, e.g. whether we author them inside variants or not |
| boolean | Use Payload | Should be True if the Stage was exported using payload files to store the actual Mesh prims. Also dictates minor behaviors when authoring the material binding relationships. |
| boolean | Remove Unreal Materials | No longer used. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
