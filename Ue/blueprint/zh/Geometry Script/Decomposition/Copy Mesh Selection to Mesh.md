---
display_name: Copy Mesh Selection to Mesh
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Decomposition](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Decomposition)

Extract the triangles identified by Selection from TargetMesh and copy/add them to StoreToSubmesh

Target is Geometry Script Library Mesh Decomposition Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Copy to Submesh |  |
| struct | Selection |  |
| boolean | Append to Existing | if false (default), StoreToSubmesh is cleared, otherwise selected triangles are appended |
| boolean | Preserve Group IDs | if true, GroupIDs of triangles on TargetMesh are preserved in StoreToSubmesh. Otherwise new GroupIDs are allocated. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Copy to Submesh |  |
| object | Target Mesh |  |
