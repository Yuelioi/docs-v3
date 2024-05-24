---
display_name: Get Parent Transform
order: 63
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns the global current or initial value for a given key.
If the element does not have a parent FTransform::Identity will be returned.

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | In Key | The key of the element to retrieve the transform for |
| boolean | Initial | If true the initial transform will be used |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | The element's parent's global current or initial transform's value. |
