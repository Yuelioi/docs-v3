---
display_name: Set Control Preferred Euler Angles by Index
order: 127
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets a control's preferred euler angles (local transform rotation)

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | In Element Index | The element index to look up |
| vector | In Euler Angles | The new preferred euler angles to set |
| enum | In Rotation Order | The rotation order to use when setting the euler angles |
| boolean | Initial | If true we'll return the preferred euler angles for the initial - otherwise current transform |
| boolean | Fix Euler Flips | If true the new euler angles value will use the shortest path |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
