---
title: Set World Rotation
order: 75
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

- Put this component at the specified rotation in world space. Updates relative rotation to achieve the final world rotation.
  \*

Target is Scene Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| rotator | New Rotation | New rotation in world space for the component. * |
| boolean | Sweep | Whether we sweep to the destination (currently not supported for rotation). * |
| boolean | Teleport | Whether we teleport the physics state (if physics collision is enabled for this object).  *If true, physics velocity for this object is unchanged (so ragdoll parts are not affected by change in location).*  If false, physics velocity is updated based on the change in position (affecting ragdoll parts). * If CCD is on and not teleporting, this will affect objects along the entire sweep volume. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Sweep Hit Result | Hit result from any impact if sweep is true. * |
