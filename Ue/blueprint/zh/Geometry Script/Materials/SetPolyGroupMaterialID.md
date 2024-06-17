---
title: SetPolyGroupMaterialID
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Set a new MaterialID on all the triangles of TargetMesh with the given PolyGroup.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Group Layer | PolyGroup Layer to use as basis for PolyGroups |
| integer | Poly Group ID | PolyGroup ID that specifies Triangles to set to new MaterialID |
| integer | Material ID | explicit new MaterialID to set |
| boolean | Defer Change Notifications | if true, the UDynamicMesh does not emit a change event/signal for this modification |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Poly Group ID |  |
| object | Target Mesh |  |
