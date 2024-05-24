---
display_name: Find Quat Between Vectors
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Quat](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Quat)

Generates the 'smallest' (geodesic) rotation around a sphere between two vectors of arbitrary length.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Start | Vector the rotation starts from |
| vector | End | Vector the rotation ends at |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Quat that will rotate from Start to End |
