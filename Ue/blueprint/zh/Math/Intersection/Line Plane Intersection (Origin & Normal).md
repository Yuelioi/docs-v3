---
display_name: Line Plane Intersection (Origin & Normal)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Intersection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Intersection)

Computes the intersection point between a line and a plane.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Line Start |  |
| vector | Line End |  |
| vector | Plane Origin |  |
| vector | Plane Normal |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | T | The t of the intersection between the line and the plane |
| vector | Intersection | The point of intersection between the line and the plane |
| boolean | Return Value | True if the intersection test was successful. |
