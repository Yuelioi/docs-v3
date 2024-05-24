---
display_name: Find Quat Between Normals
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Quat](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Quat)

Generates the 'smallest' (geodesic) rotation around a sphere between two normals (assumed to be unit length).

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Start Normal |  |
| vector | End Normal |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Quat that will rotate from Start to End |
