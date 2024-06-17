---
title: Get Point Distance to Line
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector)

Find the distance from a point to the closest point on an infinite line.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Point | Point for which we find the distance to the closest point on the line. |
| vector | Line Origin | Point of reference on the line. |
| vector | Line Direction | Direction of the line. Not required to be normalized. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | The distance from the given point to the closest point on the line. |
