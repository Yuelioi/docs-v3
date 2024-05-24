---
display_name: Get Controller
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns a controller for this hierarchy.
Note: If the controller is not available this will return nullptr
even if the bCreateIfNeeded flag is set to true. You can check the
controller's availability with IsControllerAvailable().

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Create if Needed | Creates a controller if needed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The Controller for this hierarchy |
