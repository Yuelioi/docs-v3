---
display_name: Bind Visibility to Activation
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Activatable Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ActivatableWidget)

Bind our visibility to the activation of another widget, useful for making mouse collisions behave similiar to console navigation w.r.t activation
Will immediately update visibility based on the bound widget activation & visibilites set by SetBindVisibilities.

Target is Common Activatable Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Activatable Widget | The widget whose activation / deactivation will modify our visibility |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
