---
title: Is Object Valid
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Validation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetValidation)

Runs registered validators on the provided object.
Does not add anything to any FMessageLog tabs.

Target is Editor Validator Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | In Object |  |
| enum | In Validation Usecase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Validation Errors |  |
| text | Validation Warnings |  |
| enum | Return Value | Returns Valid if the object contains valid data; returns Invalid if the object contains invalid data; returns NotValidated if no validations was performed on the object |
