---
display_name: Snap To Grid (Float)
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Float](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Float)

Snaps a value to the nearest grid multiple. E.g.,
Location = 5.1, GridSize = 10.0 : return value = 10.0
If GridSize is 0 Location is returned
if GridSize is very small precision issues may occur.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| real | Location |  |
| real | Grid Size |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Snaps a value to the nearest grid multiple. E.g.,Location = 5.1, GridSize = 10.0 : return value = 10.0If GridSize is 0 Location is returnedif GridSize is very small precision issues may occur. |
