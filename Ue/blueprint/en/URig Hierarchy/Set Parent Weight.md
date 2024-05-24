---
display_name: Set Parent Weight
order: 156
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets the weight of a parent below a multi parent element

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the multi parented element |
| struct | In Parent | The key of the parent to look up the weight for |
| struct | In Weight | The new weight to set for the parent |
| boolean | Initial | If true the initial weights will be used |
| boolean | Affect Children | If set to false children will not move (maintain global). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if changing the weight was successful |
