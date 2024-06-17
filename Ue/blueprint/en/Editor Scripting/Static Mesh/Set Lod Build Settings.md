---
title: Set Lod Build Settings
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/StaticMesh)

Set the LOD build options for the specified LOD index.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Mesh to process. |
| integer | Lod Index | The LOD we will apply the build settings. |
| struct | Build Options | The build settings we want to apply to the LOD. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
