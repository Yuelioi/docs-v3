---
display_name: ApplySimplifyToPolyGroupTopology
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Simplification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Simplification)

Simplifies the mesh down to the PolyGroup Topology. For example, the high-level faces of the mesh PolyGroups.
Another example would be on a default Box-Sphere where simplifying to PolyGroup topology produces a box.

Target is Geometry Script Library Mesh Simplify Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| struct | Group Layer |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Simplifies the mesh down to the PolyGroup Topology. For example, the high-level faces of the mesh PolyGroups.Another example would be on a default Box-Sphere where simplifying to PolyGroup topology produces a box. |
