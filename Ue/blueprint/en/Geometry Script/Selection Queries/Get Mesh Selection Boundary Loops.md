---
display_name: Get Mesh Selection Boundary Loops
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Selection Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/SelectionQueries)

Compute the set of Vertex Loops bordering a Mesh Selection. Both the 3D polylines and lists of vertex indices are returned for each Loop.
Note that for a Vertex selection this will function return the border loops around the set of vertex triangle one-rings.

Target is Geometry Script Library Mesh Selection Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Index Loops | for each discovered Loop, the IndexList of mesh vertex indices around the loop is returned here |
| struct | Path Loops | for each discovered Loop, the PolyPath of mesh vertex positions around the loop is returned here. The ordering for each loop is the same as IndexLoops. |
| integer | Num Loops | number of loops found is returned here |
| boolean | Found Errors | true is returned here if topological errors were found during loop computation. In this case the Loop set may be incomplete. |
| object | Target Mesh |  |
