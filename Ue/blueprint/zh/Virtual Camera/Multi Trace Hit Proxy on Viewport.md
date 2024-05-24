---
display_name: Multi Trace Hit Proxy on Viewport
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1)

Traces from the viewport and returns all components that contribute to the pixels surrounding InScreenPosition.
The size of the pixel area checked is controlled by InQueryParams.HitProxySize.

This finds actors that have NoCollision set. The actor is found by determining which actors contribute to the specified pixel.
This function is designed for Editor builds; in Runtime builds, it returns false.

Target is VCam Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | In Screen Position | The viewport position to trace |
| enum | In Target Viewport | The viewport to trace in |
| struct | In Query Params | Parameters for how the actors should be queried |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Result | The result, set if this function returns true. |
| boolean | Return Value | Whether Result was written to |
