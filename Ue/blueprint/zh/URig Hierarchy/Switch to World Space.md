---
display_name: Switch to World Space
order: 172
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Switches a multi parent element to world space.
This injects a world space reference.

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the multi parented element |
| boolean | Initial | If true the initial weights will be used |
| boolean | Affect Children | If set to false children will not move (maintain global). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if changing the weight was successful |
