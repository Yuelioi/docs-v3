---
display_name: Add Named Device Visualization Component Blocking
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [XR](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XR) > [Devices](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XR/Devices)

Spawns a render component for the specified XR device.

NOTE: The associated XR system backend has to provide a model for this to
work - if one is not available for the specific device, then this
will fail and return an invalid (null) object.

Target is XRAsset Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target | The intended owner for the component to attach to. |
| name | System Name | (optional) Targets a specific XR system (i.e. 'Oculus', 'OpenXR', etc.). If left as 'None', then the first system found that can render the device will be used. |
| name | Device Name | Source name of the specific device - expect the same names that the MotionControllerComponent's "MotionSource" field uses ('Left', 'Right', etc.). |
| boolean | Manual Attachment | If set, will leave the component unattached (mirror's the same option on the generic AddComponent node). When unset the component will attach to the actor's root. |
| transform | Relative Transform | Specifies the component initial transform (relative to its attach parent). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | XRDevice Id |  |
| object | Return Value | A new component representing the specified device (invalid/null if a model for the device doesn't exist). |
