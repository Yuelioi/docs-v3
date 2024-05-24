---
display_name: Expand Contract Mesh Selection
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Grow or Shrink the Selection on the TargetMesh to connected neighbours.
For Vertex selections, Expand includes vertices in one-ring of selected vertices, and Contract removes any vertices with a one-ring neighbour that is not selected
For Triangle selections, Add/Remove Triangles connected to selected Triangles
For PolyGroup selections, Add/Remove PolyGroups connected to selected PolyGroups

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| integer | Iterations | number of times to Expand/Contract the Selection. Valid range is \[0,100\] where 0 is a no-op. |
| boolean | Contract | if true selection contracts instead of growing |
| boolean | Only Expand to Face Neighbours | if true, only adjacent Triangles/PolyGroups directly connected by an edge are added, vs connected to any selected vertex |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Selection |  |
| object | Target Mesh |  |
