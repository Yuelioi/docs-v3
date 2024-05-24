---
display_name: Import LOD
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/StaticMesh)

Import or re-import a LOD into the specified base mesh. If the LOD do not exist it will import it and add it to the base static mesh. If the LOD already exist it will re-import the specified LOD.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Base Static Mesh |  |
| integer | LODIndex |  |
| string | Source Filename |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | the index of the LOD that was imported or re-imported. Will return INDEX_NONE if anything goes bad. |
