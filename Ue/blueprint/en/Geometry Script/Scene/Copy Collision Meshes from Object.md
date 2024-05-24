---
display_name: Copy Collision Meshes from Object
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Scene)

Extract the Collision Geometry from FromObject and copy/approximate it with meshes stored in ToDynamicMesh.
For Simple Collision, FromObject can be a StaticMesh Asset or any PrimitiveComponent
For Complex Collision, FromObject can be a StaticMesh Asset, StaticMeshComponent, or DynamicMeshComponent

Target is Geometry Script Library Scene Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Object |  |
| object | To Dynamic Mesh |  |
| boolean | Transform to World | if true, output mesh is in World space |
| boolean | Use Complex Collision | if true, complex collision is extracted, otherwise Simple collision shapes are meshed |
| integer | Sphere Resolution | determines tessellation density of sphere and capsule shapes |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| transform | Local to World | local-to-world transform is returned here (whether mesh is in local or world space) |
| object | Dynamic Mesh |  |
