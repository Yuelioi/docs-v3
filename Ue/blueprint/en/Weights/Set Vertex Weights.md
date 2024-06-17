---
title: Set Vertex Weights
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Weights](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Weights)

Set bone weights for a single vertex. The weights are stored as supplied and not normalized until
either "CommitWeightsToSkeletalMesh()" or "NormalizeVertexWeights()" is called.

Target is Skin Weight Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Vertex ID | the index of the vertex |
| name | In Weights | a map of Bone-Name to Weight for all bones that influence the specified vertex, ie {"Head": 0.6, "Neck": 0.4} |
| boolean | Replace All | if true, all weights on this vertex will be replaced with the input weights. Default is false. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
