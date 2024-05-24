---
display_name: Set Control Preferred Rotator by Index
order: 131
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets a control's preferred rotator (local transform rotation)

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | In Element Index | The element index to look up |
| rotator | In Rotator | The new preferred rotator to set |
| boolean | Initial | If true we'll return the preferred rotator for the initial - otherwise current transform |
| boolean | Fix Euler Flips | If true the new rotator value will use the shortest path |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
