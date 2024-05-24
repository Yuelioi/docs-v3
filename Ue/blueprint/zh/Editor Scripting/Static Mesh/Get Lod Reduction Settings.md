---
display_name: Get Lod Reduction Settings
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/StaticMesh)

Copy the reduction options with the specified LOD reduction settings.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Mesh to process. |
| integer | Lod Index | The LOD we get the reduction settings. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Reduction Options | The reduction settings where we copy the reduction options. |
