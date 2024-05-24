---
display_name: Get All Triangle Indices
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

- Returns a TriangleList of all Triangle Vertex ID triplets in a mesh.
  \*

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| boolean | Skip Gaps | if false there will be a one-to-one correspondence between Triangle ID and entries in the triangle list and invalid triplets of (-1,-1,-1) will correspond to Triangle IDs not found in the Target Mesh. * |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Triangle List |  |
| boolean | Has Triangle IDGaps | will be false on return if the mesh had no gaps in Triangle IDs or if bSkipGaps was set to true. |
| object | Target Mesh |  |
