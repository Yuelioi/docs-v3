---
display_name: Polygons Morphology Close
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Polygon List](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolygonList)

Apply a morphological "close" operator to a list of closed polygons -- first offsetting by +Offset, then by -Offset. If Offset is negative, this will instead function as an 'Open' operation

Target is Geometry Script Library Polygon List Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Polygon List |  |
| struct | Offset Options |  |
| real | Offset |  |
| boolean | Copy Input on Failure |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Operation Success |  |
| struct | Return Value | Apply a morphological "close" operator to a list of closed polygons -- first offsetting by +Offset, then by -Offset. If Offset is negative, this will instead function as an 'Open' operation |
