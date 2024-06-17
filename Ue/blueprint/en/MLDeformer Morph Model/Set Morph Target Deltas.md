---
title: Set Morph Target Deltas
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MLDeformer Morph Model](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MLDeformerMorphModel)

Set the morph target model deltas as an array of 3D vectors.
These deltas are used to generate compressed morph targets internally. You typically call this method from inside
the python training script once your morph target deltas have been generated there.
Concatenate all deltas into one buffer, so like this \[morphdeltas_target0, morphdeltas_target1, ..., morphdeltas_targetN\].
This is the same as SetMorphTargetDeltaFloats, except that it takes vectors instead of floats.

Target is MLDeformer Morph Model

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Deltas | The array of 3D vectors that contains the vertex deltas. The number of items in the array must be equal to (NumMorphs * NumBaseMeshVerts). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
