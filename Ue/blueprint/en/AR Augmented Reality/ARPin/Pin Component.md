---
display_name: Pin Component
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [ARPin](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/ARPin)

Pin an Unreal Component to a location in tracking spce (i.e. the real world).

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Component to Pin | The component that should be pinned. |
| transform | Pin to World Transform | A transform (in Unreal World Space) that corresponds to a physical location where the component should be pinned. |
| object | Tracked Geometry | An optional, real-world geometry that is recognized by the AR system; any correction to the position of this geometry will be applied to the pinned component. |
| name | Debug Name | An optional name that will be displayed when this pin is being drawn for debugging purposes. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | an object representing the pin that connects \\c ComponentToPin component to a real-world location and optionally to the \\c TrackedGeometry. |
