---
display_name: Stash Debug Mesh
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh) > [Changes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh/Changes)

Store a copy of TargetMesh with name DebugMeshName.
The mesh can later be recovered via FetchDebugMesh.
@warning This function stores the mesh in a global data structure, the caller must take care to avoid storing large numbers of debug meshes

Target is Geometry Script Library Editor Dynamic Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| string | Debug Mesh Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Dynamic Mesh | Store a copy of TargetMesh with name DebugMeshName.The mesh can later be recovered via FetchDebugMesh.@warning This function stores the mesh in a global data structure, the caller must take care to avoid storing large numbers of debug meshes |
