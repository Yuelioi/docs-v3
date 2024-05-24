---
display_name: Points Are Coplanar
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Geometry)

Determines whether a given set of points are coplanar, with a tolerance. Any three points or less are always coplanar.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Points | The set of points to determine coplanarity for. |
| real | Tolerance | Larger numbers means more variance is allowed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Whether the points are relatively coplanar, based on the tolerance |
