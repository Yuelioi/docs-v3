---
display_name: Duplicate and Retarget
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [IKBatch Retarget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/IKBatchRetarget)

Convenience function to run a batch animation retarget from Blueprint / Python. This function will duplicate a list of

- assets and use the supplied IK Retargeter to retarget the animation from the source to the target using the
- settings in the provided IK Retargeter asset.

Target is IKRetarget Batch Operation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Assets to Retarget | A list of animation assets to retarget (sequences, blendspaces or montages) * |
| object | Source Mesh | The skeletal mesh with desired proportions to playback the assets to retarget * |
| object | Target Mesh | The skeletal mesh to retarget the animation onto. * |
| object | IKRetarget Asset | The IK Retargeter asset with IK Rigs appropriate for the source and target skeletal mesh * |
| string | Search | A string to search for in the file name (replaced with "Replace" string) * |
| string | Replace | A string to replace with in the file name * |
| string | Prefix | A string to add to the start of the new file name * |
| string | Suffix | A string to add at the end of the new file name * |
| boolean | Include Referenced Assets |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |
