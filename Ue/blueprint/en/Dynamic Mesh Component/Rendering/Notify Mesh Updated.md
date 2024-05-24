---
display_name: Notify Mesh Updated
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent/Rendering)

Notify the Component that it's DynamicMesh has been modified externally. This will result in all Rendering Data
for the Component being rebuilt on the next frame (internally the Scene Proxy is fully destroyed and rebuilt).

You must use this function if the mesh triangulation has been modified, or if polygroups or material assignments
have been changed, or if Normal/UV/Color topology has changed (ie new split-vertices have been introduced).
If only vertex attribute values (position, normals, UVs, colors) have been modified, then
Notify Vertex Attributes Updated can be used to do a faster update.

Target is Dynamic Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
