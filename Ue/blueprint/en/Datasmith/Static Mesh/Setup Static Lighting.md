---
display_name: Setup Static Lighting
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/StaticMesh)

Setup the Lightmap UVs settings to enable or disable the lightmap generation on the static meshes found in the Assets list

Target is Datasmith Static Mesh Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Objects |  |
| boolean | Apply Changes | Indicates if changes must be apply or not. |
| boolean | Generate Lightmap UVs | The value to set for the generate lightmap uvs flag. |
| real | Lightmap Resolution Ideal Ratio | The desired lightmap density ratio |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
