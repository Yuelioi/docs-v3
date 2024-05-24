---
display_name: Set Lod Reduction Settings
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/StaticMesh)

Set the LOD reduction for the specified LOD index.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Mesh to process. |
| integer | Lod Index | The LOD we will apply the reduction settings. |
| struct | Reduction Options | The reduction settings we want to apply to the LOD. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
