---
title: Set Mesh Triangle Normals
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Set the triangle-vertex normals for the given TriangleID on the TargetMesh. This will
create unique triangle-vertex normals, ie it will create hard edges / split normals in
the normal overlay for each edge of the triangle.

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |
| struct | Normals |  |
| boolean | Defer Change Notifications | if true, no mesh change notification will be sent. Set to true if changing many normals in a loop. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Triangle | will be returned as false if TriangleID does not refer to a valid triangle |
| object | Target Mesh |  |
