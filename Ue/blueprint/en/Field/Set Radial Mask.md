---
title: Set Radial Mask
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

This function first defines a radial integer field equal to Interior-value inside a sphere / Exterior-value outside. This field will be used alongside the particle input value and the mask condition to compute the particle output value.

- If Mask-condition = set-always : the particle output value will be equal to Interior-value if the particle position is inside a sphere / Exterior-value otherwise.
- If Mask-condition = merge-interior : the particle output value will be equal to Interior-value if the particle position is inside the sphere or if the particle input value is already Interior-Value / Exterior-value otherwise.
- If Mask-condition = merge-exterior : the particle output value will be equal to Exterior-value if the particle position is outside the sphere or if the particle input value is already Exterior-Value / Interior-value otherwise.

Target is Radial Int Mask

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Mask Radius | Radius of the radial field |
| vector | Center Position | Center position of the radial field" |
| integer | Interior Value | If the sample distance from the center is less than radius, the intermediate value will be set the interior value |
| integer | Exterior Value | If the sample distance from the center is greater than radius, the intermediate value will be set the exterior value |
| enum | Mask Condition | If the mask condition is set to always the output value will be the intermediate one. If set to not interior/exterior the output value will be the intermediate one if the input is different from the interior/exterior value |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
