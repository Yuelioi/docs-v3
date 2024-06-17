---
title: Set Lod from Static Mesh
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Adds or create a LOD at DestinationLodIndex using the geometry from SourceStaticMesh SourceLodIndex

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Destination Static Mesh | The static mesh to set the LOD in. |
| integer | Destination Lod Index | The index of the LOD to set. |
| object | Source Static Mesh | The static mesh to get the LOD from. |
| integer | Source Lod Index | The index of the LOD to get. |
| boolean | Reuse Existing Material Slots | If true, sections from SourceStaticMesh will be remapped to match the material slots of DestinationStaticMesh when they have the same material assigned. If false, all material slots of SourceStaticMesh will be appended in DestinationStaticMesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The index of the LOD that was set. It can be different than DestinationLodIndex if it wasn't a valid index. A negative value indicates that the LOD was not set. See log for explanation. |
