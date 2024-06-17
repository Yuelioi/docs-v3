---
title: Get Control Preferred Euler Angles by Index
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns a control's preferred euler angles (local transform rotation)

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | In Element Index | The element index to look up |
| enum | In Rotation Order | The rotation order to use when retrieving the euler angles |
| boolean | Initial | If true we'll return the preferred euler angles for the initial - otherwise current transform |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Returns the current preferred euler angles |
