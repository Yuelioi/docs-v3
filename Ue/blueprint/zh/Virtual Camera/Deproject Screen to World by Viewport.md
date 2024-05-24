---
display_name: Deproject Screen to World by Viewport
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1)

Converts 2D screen position to World Space 3D position and direction in the specified viewport. Returns false if unable to determine value. Only works in editor builds.

Target is VCam Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector2d struct | In Screen Position |  |
| enum | Target Viewport |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out World Position |  |
| vector | Out World Direction |  |
| boolean | Return Value | Converts 2D screen position to World Space 3D position and direction in the specified viewport. Returns false if unable to determine value. Only works in editor builds. |
