---
display_name: Compact Material IDs
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Compact the MaterialIDs of the TargetMesh, ie remove any un-used MaterialIDs and remap the remaining
N in-use MaterialIDs to the range \[0,N-1\]. Optionally compute a Compacted list of Materials.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Source Material List | Input Material list, assumption is that SourceMaterialList.Num() == number of MaterialIDs on mesh at input |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Compacted Material List | new Compacted Material list, one-to-one with new compacted MaterialIDs |
| object | Target Mesh |  |
