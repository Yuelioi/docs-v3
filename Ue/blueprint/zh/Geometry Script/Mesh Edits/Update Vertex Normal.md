---
title: Update Vertex Normal
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Update the Normals and/or Tangents at VertexID of TargetMesh. Note that the specified vertex may have "split normals"
or "split tangents", ie in the case of hard/crease normals, UV seams, and so on. In these situations, by default
each of the unique normals/tangents at the vertex will be updated, but they will not be "merged", ie they will remain split.
However if bMergeSplitValues=true, then the vertex will be "un-split", ie after the function call the vertex will have
a single unique shared normal and/or tangents.

Note that this function requires that some normals/tangents already exist on the TargetMesh. If this is not the case,
functions like SetPerVertexNormals and ComputeTangents can be used to initialize the normals/tangents first.

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Vertex ID |  |
| boolean | Update Normal | if true (default) then the normals overlay is updated |
| vector | New Normal | the new normal vector. This vector will not be normalized, it must be normalized by the calling code. |
| boolean | Update Tangents | if true then the tangents overlay will be updated. If the tangents overlay does not exist, this function returns an error. |
| vector | New Tangent X | the new tangent vector. This vector will not be normalized, it must be normalized by the calling code. |
| vector | New Tangent Y | the new bitangent/binormal vector. This vector will not be normalized, it must be normalized by the calling code. |
| boolean | Merge Split Values | if true, any split normals/tangents at the vertex will be cleared, and a unique normal/tangent element will be set in the connected triangles |
| boolean | Defer Change Notifications | if true, no mesh change notification will be sent. Set to true if changing many normals in a loop. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Vertex | will be set to true on return if the VertexID was valid, ie had valid normals and tangents |
| object | Target Mesh |  |
