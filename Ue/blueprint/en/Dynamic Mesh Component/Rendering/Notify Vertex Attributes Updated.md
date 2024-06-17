---
title: Notify Vertex Attributes Updated
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent/Rendering)

Notify the Component that vertex attribute values of it's DynamicMesh have been modified externally. This will result in
Rendering vertex buffers being updated. This update path is more efficient than doing a full Notify Mesh Updated.

@warning it is invalid to call this function if (1) the mesh triangulation has also been changed, (2) triangle MaterialIDs have been changed,
or (3) any attribute overlay (normal, color, UV) topology has been modified, ie split-vertices have been added/removed.
Behavior of this function is undefined in these cases and may crash. If you are unsure, use Notify Mesh Updated.

Target is Dynamic Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Positions |  |
| boolean | Normals |  |
| boolean | UVs |  |
| boolean | Colors |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
