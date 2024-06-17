---
title: Slice Procedural Mesh
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Procedural Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/ProceduralMesh)

Slice the ProceduralMeshComponent (including simple convex collision) using a plane. Optionally create 'cap' geometry.

Target is Kismet Procedural Mesh Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Proc Mesh | ProceduralMeshComponent to slice |
| vector | Plane Position | Point on the plane to use for slicing, in world space |
| vector | Plane Normal | Normal of plane used for slicing. Geometry on the positive side of the plane will be kept. |
| boolean | Create Other Half | If true, an additional ProceduralMeshComponent (OutOtherHalfProcMesh) will be created using the other half of the sliced geometry |
| enum | Cap Option | If and how to create 'cap' geometry on the slicing plane |
| object | Cap Material | If creating a new section for the cap, assign this material to that section |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Other Half Proc Mesh | If bCreateOtherHalf is set, this is the new component created. Its owner will be the same as the supplied InProcMesh. |
