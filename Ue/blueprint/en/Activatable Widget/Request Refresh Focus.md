---
display_name: Request Refresh Focus
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Activatable Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ActivatableWidget)

Ask for focus to be re-set to our current DesiredFocusTarget,
but only if our node is currently the leaf-most active node (no stealing!).
This is useful for complex cases like: the buttons animate in from off-screen,
or the buttons are deeply nested in a multi-switcher hierarchy and it would be burdensome
to wrap each element in a CommonActivatableWidget.

Target is Common Activatable Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
