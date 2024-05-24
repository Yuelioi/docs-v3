---
display_name: Get Local Transform by Index
order: 50
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns the local current or initial value for a element index.
If the index is invalid FTransform::Identity will be returned.

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | In Element Index | The index to retrieve the transform for |
| boolean | Initial | If true the initial transform will be used |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | The local current or initial transform's value. |
