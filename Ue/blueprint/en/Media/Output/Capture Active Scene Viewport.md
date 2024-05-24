---
display_name: Capture Active Scene Viewport
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Output](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/Output)

Stop the current capture if there is one.
Then find and capture every frame from active SceneViewport.
It can only find a SceneViewport when you play in Standalone or in "New Editor Window PIE".
If the active SceneViewport is destroyed, the capture will stop.
The SceneViewport needs to be of the same size and have the same pixel format as requested by the media output.

Target is Media Capture

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Capture Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the capture was successfully started |
