---
display_name: Override Min LOD
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Override the Min LOD of the mesh component

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | In New Min LOD | Override new MinLodModel that make sure the LOD does not go below of this value. Range from \[0, Max Number of LOD - 1\]. This will affect in the next tick update. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
