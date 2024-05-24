---
display_name: Get Common View Point
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [NDisplay](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay) > [DCRA](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay/DCRA)

Get the view origin most commonly used by viewports in this cluster.
If no viewports override the camera, this returns the default camera, or if there isn't one, the actor's root component.

Target is nDisplay Root Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Get the view origin most commonly used by viewports in this cluster.If no viewports override the camera, this returns the default camera, or if there isn't one, the actor's root component. |
