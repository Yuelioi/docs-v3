---
title: Random Unit Vector in Cone in Degrees from Stream
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Returns a random vector with length of 1, within the specified cone, with uniform random distribution.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Stream | The random stream from which to obtain the vector. |
| vector | Cone Dir | The base "center" direction of the cone. |
| real | Cone Half Angle in Degrees | The half-angle of the cone (from ConeDir to edge), in degrees. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value |  |
