---
display_name: Update All View Visibility
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Layers)

Updates the visibility for all actors for all views.

Target is Layers Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Layer That Changed | If one layer was changed (toggled in view pop-up, etc), then we only need to modify actors that use that layer. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
