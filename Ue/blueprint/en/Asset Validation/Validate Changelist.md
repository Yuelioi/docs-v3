---
title: Validate Changelist
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Validation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetValidation)

Called to validate assets from either the UI or a commandlet.
Loads the specified assets and runs all registered validators on them.
Populates the message log with errors and warnings with clickable links.

Target is Editor Validator Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | In Changelist |  |
| struct | In Settings | Structure passing context and settings for ValidateAssetsWithSettings |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Results | More detailed information about the results of the validate assets command |
| enum | Return Value | Validation results for the changelist object itself |
