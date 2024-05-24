---
display_name: Set Morph Target Delta Floats
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MLDeformer Morph Model](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MLDeformerMorphModel)

Set the per vertex deltas, as a set of floats. Each vertex delta must have 3 floats.
These deltas are used to generate compressed morph targets internally. You typically call this method from inside
the python training script once your morph target deltas have been generated there.
Concatenate all deltas into one buffer, so like this \[morphdeltas_target0, morphdeltas_target1, ..., morphdeltas_targetN\].
The vertex ordering should be: \[(x, y, z), (x, y, z), (x, y, z)\].
This is the same as SetMorphTargetDeltas, except that this takes an array of floats instead of vectors.

Target is MLDeformer Morph Model

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Deltas | The array of floats that contains the deltas. The number of items in the array must be equal to (NumMorphs  *NumBaseMeshVerts*  3). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
