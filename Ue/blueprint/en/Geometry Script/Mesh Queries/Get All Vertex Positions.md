---
display_name: Get All Vertex Positions
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Returns a Vector List of all the mesh vertex 3D positions (possibly large!).

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| boolean | Skip Gaps | if false there will be a one-to-one correspondence between Vertex ID and entries in the Position List where a zero vector (0,0,0) will correspond to Vertex IDs not found in the Target Mesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Position List |  |
| boolean | Has Vertex IDGaps | will be false if the mesh had no gaps in Vertex IDs or if bSkipGaps was set to true. |
| object | Target Mesh |  |
