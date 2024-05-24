---
display_name: Copy Mesh To Mesh UV Channel
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Transfer the 3D vertex positions and triangles of CopyFromUVMesh to the given UV Channel identified by ToUVChannel of CopyToMesh.
3D positions (X,Y,Z) will be copied as UV positions (X,Y), ie Z is ignored.

bOnlyUVPositions controls whether only UV positions will be updated, or if the UV topology will be fully replaced.
When false, CopyFromUVMesh must currently have a MaxVertexID \<= that of the UV Channel MaxElementID
When true, CopyFromUVMesh must currently have a MaxTriangleID \<= that of CopyToMesh

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Copy from UVMesh |  |
| integer | To UV Channel |  |
| object | Copy to Mesh |  |
| boolean | Only UVPositions | if true, only (valid, matching) UV positions are updated, a full new UV topology is created |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Copy to Mesh |  |
| boolean | Found Topology Errors |  |
| boolean | Is Valid UV Channel | will be returned false if To UV Channel is not available |
| object | Copy from Mesh |  |
