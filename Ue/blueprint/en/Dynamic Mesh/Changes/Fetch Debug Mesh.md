---
display_name: Fetch Debug Mesh
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh) > [Changes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh/Changes)

Fetch a debug FDynamicMesh3 saved with DebugMeshName from the global debug mesh storage and copy to ToTargetMesh.
If DebugMeshName does not exist, a cube will be returned.

Target is Geometry Script Library Editor Dynamic Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Debug Mesh Name |  |
| object | To Target Mesh |  |
| boolean | Clear Debug Mesh | if true, debug mesh will be removed from global storage |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Debug Mesh Exists | will return as true if DebugMeshName existed |
| object | Dynamic Mesh |  |
