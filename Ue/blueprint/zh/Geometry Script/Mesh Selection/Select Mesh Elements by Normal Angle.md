---
display_name: Select Mesh Elements by Normal Angle
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Create a new Mesh Selection of the SelectionType for the TargetMesh by finding all elements that have a normal
vector that is within an angular deviation threshold from the given Normal.
For Triangle and PolyGroup selections the triangle facet normal is used, for Vertex selections the per-vertex averaged normal is used.

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| vector | Normal | normal/direction vector to measure against |
| real | Max Angle Deg | maximum angular deviation from Normal, in degrees |
| enum | Selection Type |  |
| boolean | Invert | return a selection of all elements not within the given deviation |
| integer | Min Num Triangle Points | number of vertices of a triangle that must be within the angular deviation for it to be selected (1,2, or 3) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |
