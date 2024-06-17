---
title: Make Wheel Status
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Vehicles](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Vehicles)

Make Wheel Status

Target is Chaos Wheeled Vehicle Movement Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | In Contact |  |
| object | Phys Material |  |
| real | Normalized Suspension Length |  |
| real | Spring Force |  |
| real | Slip Angle |  |
| boolean | Is Slipping |  |
| real | Slip Magnitude |  |
| boolean | Is Skidding |  |
| real | Skid Magnitude |  |
| real | Drive Torque |  |
| real | Brake Torque |  |
| boolean | ABSActivated |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Contact Point |  |
| vector | Skid Normal |  |
| struct | Return Value | Make Wheel Status |
