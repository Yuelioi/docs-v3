---
display_name: Set Forced LOD
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Set ForcedLodModel of the mesh component

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | In New Forced LOD | Set new ForcedLODModel that forces to set the incoming LOD. Range from \[1, Max Number of LOD\]. This will affect in the next tick update. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
