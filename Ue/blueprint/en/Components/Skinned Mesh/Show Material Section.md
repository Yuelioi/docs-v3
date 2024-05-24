---
display_name: Show Material Section
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Allows hiding of a particular material (by ID) on this instance of a SkeletalMesh.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Material ID | Index of the material show/hide |
| integer | Section Index |  |
| boolean | Show | True to show the material, false to hide it |
| integer | LODIndex | Index of the LOD to modify material visibility within |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
