---
title: Capture Property
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Variant Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VariantManager)

Finds the actor binding to Actor within Variant and tries capturing a property with PropertyPath
Returns the captured UPropertyValue if succeeded or nullptr if it failed.

Target is Variant Manager Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Variant |  |
| object | Actor |  |
| string | Property Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Finds the actor binding to Actor within Variant and tries capturing a property with PropertyPathReturns the captured UPropertyValue if succeeded or nullptr if it failed. |
