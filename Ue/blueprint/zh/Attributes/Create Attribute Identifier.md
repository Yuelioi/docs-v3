---
title: Create Attribute Identifier
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Attributes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Attributes)

Constructs a valid FAnimationAttributeIdentifier instance. Ensuring that the underlying BoneName exists on the Skeleton for the provided AnimationAsset.

Target is Animation Attribute Identifier Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Animation Asset | Animation asset to retrieve Skeleton from |
| name | Attribute Name | Name of the attribute |
| name | Bone Name | Name of the bone this attribute should be attributed to |
| object | Attribute Type | Type of the underlying data (to-be) stored by this attribute |
| boolean | Validate Exists on Asset | Whether or not the attribute should exist on the AnimationAsset. False by default. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Valid FAnimationCurveIdentifier if the operation was successful |
