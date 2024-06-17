---
title: GetNormalizedAttributeValue
order: 55
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [DMX](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX)

Return the normalized value of an Int value from a Fixture Patch function.

Target is DMXSubsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | In Fixture Patch |  |
| struct | In Function Attribute |  |
| integer | In Value |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | The normalized value of the passed in Int using the Function's signal format. -1.0 if the Function is not found in the Fixture Patch. |
