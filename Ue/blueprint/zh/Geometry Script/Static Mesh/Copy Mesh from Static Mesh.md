---
display_name: Copy Mesh from Static Mesh
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/StaticMesh)

Extracts a Dynamic Mesh from a Static Mesh Asset.

Note that the LOD Index in RequestedLOD will be silently clamped to the available number of LODs (SourceModel or RenderData)

Target is Geometry Script Library Static Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Static Mesh Asset |  |
| object | To Dynamic Mesh |  |
| struct | Asset Options |  |
| struct | Requested LOD |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Dynamic Mesh | Extracts a Dynamic Mesh from a Static Mesh Asset.Note that the LOD Index in RequestedLOD will be silently clamped to the available number of LODs (SourceModel or RenderData) |
