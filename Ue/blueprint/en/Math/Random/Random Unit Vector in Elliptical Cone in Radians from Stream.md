---
display_name: Random Unit Vector in Elliptical Cone in Radians from Stream
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Returns a random vector with length of 1, within the specified cone, with uniform random distribution.
The shape of the cone can be modified according to the yaw and pitch angles.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Stream | The random stream from which to obtain the vector. |
| vector | Cone Dir |  |
| real | Max Yaw in Radians | The yaw angle of the cone (from ConeDir to horizontal edge), in radians. |
| real | Max Pitch in Radians | The pitch angle of the cone (from ConeDir to vertical edge), in radians. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value |  |
