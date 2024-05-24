---
display_name: Get Force Added Columns
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Object Mixer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ObjectMixer)

Specify a list of property names found in parent classes you want to show that aren't in the specified classes.
Note that properties specified here do not override the properties specified in GetColumnsToExclude().
For example, a ULightComponent displays "LightColor" in the editor's details panel,
but ULightComponent itself doesn't have a property named "LightColor". Instead it's in its parent class, ULightComponentBase.
In this scenario, ULightComponent is specified and PropertyInheritanceInclusionOptions is None, so "LightColor" won't appear by default.
Specify "LightColor" in this function to ensure that "LightColor" will appear as a column as long as
the property is accessible to one of the specified classes regardless of which parent class it comes from.

Target is Object Mixer Blueprint Object Filter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | Specify a list of property names found in parent classes you want to show that aren't in the specified classes.Note that properties specified here do not override the properties specified in GetColumnsToExclude().For example, a ULightComponent displays "LightColor" in the editor's details panel,but ULightComponent itself doesn't have a property named "LightColor". Instead it's in its parent class, ULightComponentBase.In this scenario, ULightComponent is specified and PropertyInheritanceInclusionOptions is None, so "LightColor" won't appear by default.Specify "LightColor" in this function to ensure that "LightColor" will appear as a column as long asthe property is accessible to one of the specified classes regardless of which parent class it comes from. |
