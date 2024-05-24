---
display_name: Set Nanite Settings
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Operation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/Operation)

Set Nanite settings for selected meshes

Target is Dataprep Operations Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Selected Objects | Array of objects to process. |
| boolean | In Enabled | If true, Nanite data will be generated. |
| integer | In Position Precision | Step size is 2^(-PositionPrecision) cm. MIN_int32 is auto. |
| real | In Percent Triangles | Percentage of triangles to keep from LOD0. 1.0 = no reduction, 0.0 = no triangles. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Modified Objects | List of modified objects the processed meshes will be added to |
