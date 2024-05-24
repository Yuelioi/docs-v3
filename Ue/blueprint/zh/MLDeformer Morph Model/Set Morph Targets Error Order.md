---
display_name: Set Morph Targets Error Order
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MLDeformer Morph Model](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MLDeformerMorphModel)

Set the order of importance during LOD, for the morph targets.
Basically this specifies the sorted order of the morph targets, based on the error they introduce when disabling them.

Target is MLDeformer Morph Model

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Morph Target Order | The array of morph target indices, starting with the most important morph target, and ending with the least important morph target's index. |
| real | Error Values | The error value for each morph target (not sorted), so index 0 contains the error value of the first morph target, which isn't necesarrily the one with highest error. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
