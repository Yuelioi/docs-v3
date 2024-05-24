---
display_name: Set Skeletal Mesh
order: 48
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [IKRig](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/IKRig)

Sets the preview mesh to use. Loads the hierarchy into the asset's IKRigSkeleton.
Returns true if the mesh was able to be set. False if it was incompatible for any reason.

Target is IKRig Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the preview mesh to use. Loads the hierarchy into the asset's IKRigSkeleton.Returns true if the mesh was able to be set. False if it was incompatible for any reason. |
