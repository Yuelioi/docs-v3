---
display_name: SetPolyGroupForMeshSelection
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Groups](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyGroups)

Set a new PolyGroup on all the triangles of the given Selection, for the given GroupLayer.

Target is Geometry Script Library Mesh Polygroup Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Group Layer |  |
| struct | Selection |  |
| integer | Set Poly Group ID | explicit new PolyGroupID to set |
| boolean | Generate New Poly Group | if true, SetPolyGroupID is ignored and a new unique PolyGroupID is generated |
| boolean | Defer Change Notifications | if true, the UDynamicMesh does not emit a change event/signal for this modification |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Set Poly Group ID Out | the PolyGroupID that was set on the triangles is returned here (whether explicit or auto-generated) |
| object | Target Mesh |  |
