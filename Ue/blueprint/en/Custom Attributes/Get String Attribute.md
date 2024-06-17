---
title: Get String Attribute
order: 6
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
| string | Default Value | In case the attribute could not be found |
| enum | Lookup Type | Determines how the attribute is retrieved from the specified BoneName (see ECustomBoneAttributeLookup) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Value | Retrieved attribute value if found, otherwise is set to DefaultValue |
| boolean | Return Value | Whether or not the atttribute was successfully retrieved |
