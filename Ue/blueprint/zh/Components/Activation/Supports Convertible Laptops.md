---
title: Supports Convertible Laptops
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Activation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Activation)

Check whether the platform supports convertible laptops.

Note: This does not necessarily mean that the platform is a convertible laptop.
For example, convertible laptops running Windows 7 or older will return false,
and regular laptops running Windows 8 or newer will return true.

Target is Platform Events Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true for convertible laptop platforms, false otherwise. |
