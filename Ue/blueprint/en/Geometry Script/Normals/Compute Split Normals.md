---
display_name: Compute Split Normals
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Recompute hard edges / split-normals for TargetMesh based on the provided SplitOptions, and then
recompute the new shared triangle-vertex normals using the given CalculateOptions.
The normal recomputation is identical to calling RecomputeNormals.

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Split Options |  |
| struct | Calculate Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Recompute hard edges / split-normals for TargetMesh based on the provided SplitOptions, and thenrecompute the new shared triangle-vertex normals using the given CalculateOptions.The normal recomputation is identical to calling RecomputeNormals. |
