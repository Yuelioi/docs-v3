---
display_name: Get Object Classes to Filter
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Object Mixer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ObjectMixer)

Return the basic object types you want to filter for in your level.
For example, if you want to work with Lights, return ULightComponentBase.
If you also want to see the properties for parent or child classes,
override the GetObjectMixerPropertyInheritanceInclusionOptions and GetForceAddedColumns functions.

Target is Object Mixer Blueprint Object Filter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| class | Return Value | Return the basic object types you want to filter for in your level.For example, if you want to work with Lights, return ULightComponentBase.If you also want to see the properties for parent or child classes,override the GetObjectMixerPropertyInheritanceInclusionOptions and GetForceAddedColumns functions. |
