---
display_name: 填充与描边
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh Merging Library](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshMergingLibrary) > [Test](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshMergingLibrary/Test)

Merges meshes and bakes out materials into a atlas-material for the given set of static mesh components using the MergeSettings

Target is Editor Tests Utility Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Static Mesh Components |  |
| struct | Merge Settings |  |
| boolean | Replace Actors |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Out LODIndices |  |
