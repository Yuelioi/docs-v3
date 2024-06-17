---
title: Is Asset Valid
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Validation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetValidation)

Loads the object referred to by the provided AssetData and runs registered validators on it.
Does not add anything to any FMessageLog tabs.

Target is Editor Validator Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Asset Data |  |
| enum | In Validation Usecase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Validation Errors |  |
| text | Validation Warnings |  |
| enum | Return Value | Returns Valid if the object pointed to by AssetData contains valid data; returns Invalid if the object contains invalid data or does not exist; returns NotValidated if no validations was performed on the object |
