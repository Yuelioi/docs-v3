---
display_name: Update Actor Visibility
order: 54
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataLayers)

Updates the provided actors visibility in the viewports

Target is Data Layer Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor | Actor to update |
| boolean | Notify Selection Change | If true the Editor is notified of the selection change; if false, the Editor will not be notified |
| boolean | Redraw Viewports | If true the viewports will be redrawn; if false, they will not |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Out Selection Changed | \[OUT\] Whether the Editors selection changed |
| boolean | Out Actor Modified | \[OUT\] Whether the actor was modified |
| boolean | Return Value |  |
