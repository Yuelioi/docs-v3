---
title: Remap to New Material IDs by Material
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Remap the Material IDs of the TargetMesh to a new set of Material IDs based on a 'From'/Current Material List, and a New Material List.
For each triangle, the current Material is determined as FromMaterialList\[MaterialID\], and then the first index of this Material is found
in the ToMaterialList, and this index is used as the new MaterialID

If a Material cannot be found in ToMaterialList, a warning will be printed and the MaterialID left unmodified,
unless MissingMaterialID is set to a value >= 0, in which case MissingMaterialID will be assigned

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | From Material List |  |
| object | To Material List |  |
| integer | Missing Material ID |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Remap the Material IDs of the TargetMesh to a new set of Material IDs based on a 'From'/Current Material List, and a New Material List.For each triangle, the current Material is determined as FromMaterialList\[MaterialID\], and then the first index of this Material is foundin the ToMaterialList, and this index is used as the new MaterialIDIf a Material cannot be found in ToMaterialList, a warning will be printed and the MaterialID left unmodified,unless MissingMaterialID is set to a value >= 0, in which case MissingMaterialID will be assigned |
