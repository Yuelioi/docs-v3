---
display_name: Set Target Landscape
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LandscapeManager)

Adds the brush to the given landscape, removing it from any previous one. This differs from SetOwningLandscape
in that SetOwningLandscape is called by the landscape itself from AddBrushToLayer to update the manager.

Target is Landscape Patch Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Owning Landscape |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
