---
display_name: Create Circle Path 3D
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Path](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyPath)

Create a closed circle around the origin on the XY plane, then transformed by Transform.
By our convention for closed paths, the end vertex is *not* a duplicate of the start vertex.

Target is Geometry Script Library Poly Path Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| transform | Transform |  |
| real | Radius |  |
| integer | Num Points |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Poly Path | Create a closed circle around the origin on the XY plane, then transformed by Transform.By our convention for closed paths, the end vertex is *not* a duplicate of the start vertex. |
