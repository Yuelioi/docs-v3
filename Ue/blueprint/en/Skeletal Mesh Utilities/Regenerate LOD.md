---
display_name: Regenerate LOD
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Skeletal Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SkeletalMeshUtilities)

Regenerate LODs of the mesh

Target is Skeletal Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Skeletal Mesh | The mesh that will regenerate LOD |
| integer | New LODCount | Set valid value (>0) if you want to change LOD count. Otherwise, it will use the current LOD and regenerate |
| boolean | Regenerate Even if Imported | If this is true, it only regenerate even if this LOD was imported before If false, it will regenerate for only previously auto generated ones |
| boolean | Generate Base LOD | If this is true and there is some reduction data, the base LOD will be reduce according to the settings |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if succeed. If mesh reduction is not available this will return false. |
