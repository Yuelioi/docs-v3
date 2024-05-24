---
display_name: Copy Mesh UV Channel To Mesh
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Copy the 2D UVs from the given UV Channel in CopyFromMesh to the 3D vertex positions in CopyToUVMesh,
with the triangle mesh topology defined by the UV Channel. Generally this "UV Mesh" topology will not
be the same as the 3D mesh topology. PolyGroup IDs and Material IDs are preserved in the UVMesh.

2D UV Positions are copied to 3D as (X, Y, 0)

CopyMeshToMeshUVChannel will copy the 3D UV Mesh back to the UV Channel. This pair of functions can
then be used to implement UV generation/editing via other mesh functions.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Copy from Mesh |  |
| integer | UV Channel |  |
| object | Copy to UV Mesh |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Copy to UV Mesh |  |
| boolean | Invalid Topology | will be returned true if any topological issues were found |
| boolean | Is Valid UVSet | will be returned false if UVSetIndex is not available |
| object | Copy from Mesh |  |
