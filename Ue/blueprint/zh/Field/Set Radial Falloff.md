---
title: Set Radial Falloff
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

Sphere scalar field that will be defined only within a sphere

Target is Radial Falloff

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Field Magnitude | Magnitude of the sphere falloff field |
| real | Min Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Max Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Default Value | The field value will be set to Default if the sample distance from the center is higher than the radius |
| real | Sphere Radius | Radius of the sphere falloff field |
| vector | Center Position | Center position of the sphere falloff field |
| enum | Falloff Type | Type of falloff function used if the falloff function is picked |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
