---
display_name: Get Control Preferred Euler Rotation Order by Index
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns a control's preferred euler rotation order

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | In Element Index | The element index to look up |
| boolean | From Settings | If true the rotation order will be looked up from the control's settings, otherwise from the currently set animation value |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| enum | Return Value | Returns the current preferred euler rotation order |
