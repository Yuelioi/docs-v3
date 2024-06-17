---
title: Is Action for Blueprints
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Assets](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Assets)

Returns whether or not this action is designed to work specifically on Blueprints (true) or on all assets (false).
If true, GetSupportedClass() is treated as a filter against the Parent Class of selected Blueprint assets.
Note: Returns the value of bIsActionForBlueprints by default.

Target is Asset Action Utility

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns whether or not this action is designed to work specifically on Blueprints (true) or on all assets (false).If true, GetSupportedClass() is treated as a filter against the Parent Class of selected Blueprint assets.@note Returns the value of bIsActionForBlueprints by default. |
