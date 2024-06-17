---
title: Get String Attribute Ref
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Custom Attributes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CustomAttributes)

Get string type attribute value.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone Name | Name of the bone to retrieve try and retrieve the attribute from |
| name | Attribute Name | Name of the attribute to retrieve |
| string | Out Value | (reference) Retrieved attribute value if found, otherwise is set to DefaultValue |
| enum | Lookup Type | Determines how the attribute is retrieved from the specified BoneName (see ECustomBoneAttributeLookup) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not the atttribute was successfully retrieved |
